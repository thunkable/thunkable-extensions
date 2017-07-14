# Contribution guidelines
This repository is intended to be for Thunkable extensions which are being considered for incorporation as Thunkable components.  

Note that this is a public open source repository using the Apache 2 license.  If you put your code in this repo your extension source can be freely used by anybody for any pupose.  Please make sure that your source code files contain a mention of the license by putting some comments near the top such as:
```
// Released under the Apache License, Version 2.0
// http://www.apache.org/licenses/LICENSE-2.0
```
See the [LICENSE](./LICENSE) file in this directory for the gory details of the Apache 2 license.

Please place extension source files in directory paths which reflect the package names that the source files use.  For example, if a source file has a package statement like:
```
package com.mycompany.myproject.myextension;
```
then put your file in `com/mycompany/myproject/myextension`.

If you have any documentation for your extension, please include in the same main directory as your source code.  A `README` file would be a good place to put that documentation but it can have any name you like, as long as it is clear what it is.

If you require any libraries for your extension, please note that in your documentation or a pull request comment and provide a link to the documentation for those libraries and links to download the libraries themselves.  Do not include the libraries themselves in your pull request.  We need to verify that the libraries are form a reasonably safe and trustworthy source and will download them ourselves.

Also note that if a pull request is accepted into this repo there is no guarantee that it will be incorporated by Thunkable for use as a component or that if it is used that it will maintain identical functionality as the extension.

Despite all the caveats and warnings above, **we very much appreciate all the work that you have put into your extensions and your willingness to publish them in this repository!**
