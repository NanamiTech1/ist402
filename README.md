# HAXcms microsite
This is a HAXcms generated and managed micro-site. It can run on it's own but it was generated by a HAXcms system somewhere.

## Course Description
IST 402, Emerging Issues and Technology, is a course dedicated to focusing on relevant and current technology and the issues surrounding technology currently. The course is taught in person in a weekly session from 4:00 - 7:00 PM in CEDAR Building 134. The class is not focused on programming, but it is focused on topics surrounding programming. Topics discussed in this course are chosen by the Professor and include topics such as Accessibility, Building a Digital Identity, Web Development, and Version Control software to name a few.

## Developer mode
HAXcms primary audience is people doing things entirely through the UI. It is however creating everything in a way that's very developer friendly though. This means you can peal this off from the original place it came from and run this as a stand alone repo by:

- leveraging the included package.json
- removing the symlinks to dist / node_modules / build
- copying the dist directory from the project root into your local setup: https://github.com/elmsln/haxcms/tree/master/dist

Using this approach you'll have to manage dependencies on your own but you'll be able to utilize custom themes / elements that you can to show up. If you do add any new elements or themes you'll need to ship this repo with the `polymer build` command executed in order to bundle / compile everything together for usage.

### special note
The CDN mirrors for HAXcms may or may not include the elements you wish to extend your project with so those options for rapid distributed publishing may not be availble.

# HAXcms
HAX CMS seeks to be the smallest possible back-end CMS to make HAX work and be able to build websites with it. Leveraging JSON Outline Schema, HAX is able to author multiple pages, which it then writes onto the file system.

### What is IST 402 (Emerging Issues in Tech)
This IST 402 class is application of our knowlege on modern day technology. We are focusing on understanding of concepts that will be applied in the working world. Then we learn how these tools are used and their benefits. This class will eventually use this knowlegde to help us learn about new technology as soon as it comes out. This will be possible because this class will give us the tools to learn these new technologies for ourselves.

## License
[Apache 2.0](LICENSE.md)

IST 402 Course Decription

This course prepares students to understand the difference between potential technological failures and success, fads and revolutionary technology. It also helps students to view emerging issues as an opportunity rather than a threat. Intellectual tools are provided to assist in understanding issues, assessing and forecasting technological changes for feasibility and planning in real world situations.
