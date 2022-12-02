# text-editor

https://morning-sierra-24415.herokuapp.com/

<img width="1159" alt="Screen Shot 2022-12-01 at 9 43 08 PM" src="https://user-images.githubusercontent.com/108489839/205203077-579db577-6374-47ba-9590-06729bc53a26.png">

# Description

For this project, I built a text editor that runs in a browser and meets PWA criteria. The application functions offline as well. I began with an existing application and implemented methods to get and store data in the database. I used a package called idb, which is a wrapper around the indexedDB API. 

# Installation

I had to edit the webpack and add the HtmlWebpackPlugin, InjectManifest, WebpackPwaManifest, and specific set of module rules. I also editted the AddEventListener functions in the install js and added logic in the database js.

# Usage

This text editor serves the user online and offline because it is a PWA. Its useful to the user because they can rely on the application to save their data and retrieve it later on. 


# License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
