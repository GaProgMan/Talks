Blazor components are a little different [to Razor Pages]. They are similar to stuff that you do on the server in that they're both using the Razor syntax. You're using C# and HTML to decide, like, what markup you want.

But on the server what's really happening is your basically generating HTML as, effectively, a string, then you're sending it down to the browser and having the browser render that HTML doing it's normal thing.

With Blazor components it's actually a little different. We take the Razor files, **these cshtml files**, and just like on the server, **they do get compiled into a class**, and it's **the class** that basically **has the compile functionality** for generating the corresponding **markup**.

But in Blazor those classes get **downloaded** actually **into the browser as a DLLs**. Whereas on the server side you're just download a string, **with Blazor you're downloading the compiled classes**.

And then client side in the browser **the Blazor runtime will ask components to render** and those components will render their markup, using the logic that you specify, **into a Rendering Tree**. And then **Blazor's runtime will handle updating the DOM in the browser, based on off of that rendering tree**.

And **as components change, and they re-render themselves, [Blazor’s runtime] will diff the new Rendering Tree that the component just created with the current one and update the DOM accordingly**, making it very efficient so you're not touching the DOM too much. Like, you're basically doing it as little as you can.