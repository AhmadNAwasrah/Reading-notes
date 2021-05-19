#  Local Storage 

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXpBSDn4B4bzVWTj8Scpnvxiu4GZbxMJGy-w&usqp=CAU)

There are many different options for storing data in the browser 
There are several  storage mechanisms available in the browser/

- SessionStorage is tab specific, and scoped to the lifetime of the tab. It may be useful for storing small amounts of session specific information, for example an IndexedDB key. It should be used with caution because it is synchronous and will block the main thread. It is limited to about 5MB and can contain only strings. Because it is tab specific, it is not accessible from web workers or service workers. 
- LocalStorage should be avoided because it is synchronous and will block the main thread. It is limited to about 5MB and can contain only strings. LocalStorage is not accessible from web workers or service workers.
- Cookies have their uses, but should not be used for storage. Cookies are sent with every HTTP request, so storing anything more than a small amount of data will significantly increase the size of every web request. They are synchronous, and are not accessible from web workers. Like LocalStorage and SessionStorage, cookies are limited to only strings. 
- The File System API and FileWriter API provide methods for reading and writing files to a sandboxed file system. While it is asynchronous, it is not recommended because it is only available in Chromium-based browsers. 
- The File System Access API was designed to make it easy for users to read and edit files on their local file system. The user must grant permission before a page can read or write to any local file, and permissions are not persisted across sessions.

 
 - WebSQL should not be used, and existing usage should be migrated to IndexedDB. Support has been removed from almost all major browsers 


## TRACKING CHANGES TO THE HTML5 STORAGE AREA 
The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. (If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped. If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event 
![img](https://image.slidesharecdn.com/html5localstorage-140511235722-phpapp01/95/html5-local-storage-12-638.jpg?cb=1399852926)


## HTML5 STORAGE IN ACTION
 

It is limited to about 5MB and can contain only strings. Because it is tab specific, it is not accessible from web workers or service workers. LocalStorage should be avoided because it is synchronous and will block the main thread. It is limited to about 5MB and can contain only  

## BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS 
 HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visions.

One vision is an acronym that you probably know already: SQL. In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite. This early prototype later influenced the creation of the Web SQL Database specification. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, 



