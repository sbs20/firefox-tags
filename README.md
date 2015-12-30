# firefox-tags
You have previously imported tag based bookmarks / favourites from google or delicious
and Firefox has arranged them in folders. Where you had a single bookmark with multiple
tags, now you have multiple folders with the same bookmark.

Firefox now supports tags. This program will take a JSON export of your Firefox bookmarks,
flatten them into a deduplicated list, and assign the folder names as tags. Take the JSON
output and import it back into Firefox.

Be sure to make a back up of your original JSON export so that you can re-import it if
everything goes wrong. Remember, it's not my fault.

# The MIT License (MIT)
Copyright 2015	Sam Strachan (sam.strachan@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Acknowledgements
Although lightly refactored, this uses the JSON formatter Copyright (c) 2008 Vladimir Bodurov
https://quickjsonformatter.codeplex.com/ 