## <center>E926 Api Module</center>

(side note: this is an SFW ONLY version of [E6API](https://npmjs.org/package/E6API), the filtering is done by sending requests to e926.net instead of e621.net, you should do filtering on your side as well if you want only sfw posts, as there is no extra filtering being done!)

Currently, this module only supports fetching posts/post tags, the e926 api isn't very well documented, and it's hard to test things like creating posts, deleting posts, flagging posts, etc without getting barred from doing so, or just tossing in junk code, and hoping for the best. Some of the methods are sort of implemented, but they're commented out. I know I've done them wrong, which is why they are commented out. They were left there if I ever want to come back and try to solve them.

### This module returns only sfw posts! For no filter, see [E9API](https://npmjs.org/package/e9api), that module will not filter any posts based on ratings!

Please see [E6API](https://npmjs.org/package/e6api) for the documentation, as this is just a reskinned version of that module.