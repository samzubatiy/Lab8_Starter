# Lab8-Starter

How are graceful degradation and service workers related?  
Graceful degradation is the practice of building an application to function fully with modern capabilities, while still providing a usable experience when those capabilities are unavailable. Service workers directly support graceful degradation by acting as a network proxy that serves cached assets when the user is offline or on a slow connection. Without a service worker, losing network access would completely break the app. With one, the app degrades gracefully. Users may not get the freshest data, but the core experience still works.

