## Discourse import scripts for Askbot

I recently ported the [CVX Forum](http://ask.cvxr.com) from
[Askbot](http://askbot.com) to [Discourse](http://discourse.org). 
I was able to suck in the users, questions, comments, and even some
of the tags largely intact. Here is the code I used to do that.

The file `base.rb` is a slightly patched version of the one found in
the `script/import_scripts` directory of the Discourse source. All I
added was a slight correction to enable user-supplied location fields
to be ported from Askbot to Discourse. If you didn't use this file, 
you wouldn't lose much at all.

THIS CODE IS NOT GOING TO WORK FOR YOU. This was designed to handle
my specific situation. Indeed, even when I did the final data port,
I probably ran this code 2-3 times, with certain steps commented out,
to make sure I was happy with the intermediate results. I am not
proposing that this is a candidate for inclusion in the Discourse
source tree itself. And no issues or pull requests, please; I'm done
with this.

Still, for someone considering moving from Askbot
to Discourse, this might be helpful. I'm going create a thread on
[Discourse Meta](https://meta.discourse.org) 
to introduce this project and create discussion. Once I have done
so I will update this file with a direct link to the post. I
welcome comments and questions there.

Regards,
Michael C. Grant
http://cvxr.com



