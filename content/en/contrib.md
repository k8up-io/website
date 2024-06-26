---
title: Contribution Guide
description: The K8up Contribution Guide
---

## Submitting changes

Please submit a Pull Request at GitHub with a clear list of what you’ve done (read more about [pull requests](http://help.github.com/pull-requests/)).

## DCO

The DCO or `Sign your work` requirement is not intended as a roadblock or speed bump.

The sign-off is a simple line at the end of the explanation for the patch. Your signature certifies that you wrote the patch or otherwise have the right to pass it on as an open-source patch. The rules are pretty simple: if you can certify the below (from [developercertificate.org](http://developercertificate.org/)):

> Developer Certificate of Origin Version 1.1
>
> Copyright © 2004, 2006 The Linux Foundation and its contributors. 660 York Street, Suite 102, San Francisco, CA 94110 USA
>
> Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.
>
> Developer’s Certificate of Origin 1.1
>
> By making a contribution to this project, I certify that:
>
> \(a\) The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or
>
> \(b\) The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or
>
> \(c\) The contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.
>
> \(d\) I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.

Then you just add a line to every git commit message:

> Signed-off-by: Joe Smith &lt;[joe.smith@email.com](#)&gt;

Use your real name (sorry, no pseudonyms or anonymous contributions).

If you set your `user.name` and `user.email` git configs, you can sign your commit automatically with `git commit -s`.

Some K8up contributors might not be familiar with `git`, or have used a web based editor, and thus asking them to `git commit --amend -s` is not the best way forward.

In this case, maintainers can update the commits based on clause (c) of the DCO. The most trivial way for a contributor to allow the maintainer to do this, is to add a DCO signature in a pull requests' comment, or a maintainer can simply note that the change is sufficiently trivial that it does not substantially change the existing contribution - for example a spelling change.

When you add someone’s DCO, please also add your own to keep a log.