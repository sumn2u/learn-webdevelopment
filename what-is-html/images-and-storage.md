# Images and Storage

To add an image to an HTML document, you can use the `<img>` element and specify the URL of the image in the src attribute. The image can be stored on the same server as the HTML document, or on a different server.

If the image is stored on the same server as the HTML document, you can use a relative URL in the src attribute to specify the location of the image file. A relative URL is a URL that is relative to the current webpage, and does not include the domain name.

For example, if the HTML document is in a folder called "`html`" and the image file is in a folder called "**images**", you can use the following code to add the image to the HTML document:

```html
<img src="/images/cat.jpg" alt="A cute cat"> 
```

If the image is stored on a different server, you can use an absolute URL in the src attribute to specify the location of the image file. An absolute URL is a complete URL that includes the domain name and the path to the file.

For example, if the image file is stored on the server "[https://www.example.com](https://www.example.com/)", you can use the following code to add the image to the HTML document:

```html
<img src="https://www.example.com/images/cat.jpg" alt="A cute cat">
```

In addition to storing images on a server, you can also store images in a cloud storage service, such as Google Cloud Storage or Amazon S3. These services allow you to store and manage files in the cloud, and provide URLs that you can use to access the files from anywhere.
