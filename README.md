<!--
SPDX-FileCopyrightText: © 2025 Bart Groeneveld <avi@bartavi.nl>
SPDX-License-Identifier: CC0-1.0
-->

## [GitHub is still not reachable over IPv6.](https://en.internet.nl/site/github.com/)

[GitHub is still not reachable over IPv6.](https://en.internet.nl/site/github.com/)


### Why should it provide IPv6?

Lot's of servers and ISP's directly or indirectly depend on GitHub.[^1]
While GitHub is IPv4-only, they are required to support IPv4.
Have a cool new innovative project and want to use that way cheaper[^2] IPv6-only server?
You can't, because you most likely have to pull in something from GitHub.
Want to start a new ISP, and don't want to invest in expensive IPv4?
You can't, because someone in your network likely needs access to GitHub.

IPv4-only is basically keeping the status quo of internet: the rule of Big Tech.


### Can it provide IPv6?

GitHub is owned by one of the largest and richest companies in the world (Microsoft),
itself a software company,
with a cloud department (Azure).
So both money and expertise should not be the problem.
If they can't do it, then who can?

*Well, literally every competitor has IPv6!*

- Big commercial: GitLab and Bitbucket.
- Small and open source: [Sourcehut](https://sr.ht/).
- Non-profit: [Codeberg](https://codeberg.org/).
- Most [self-hosted](https://forgejo.org/) forges.

So GitHub, if your competition can do it with far less money and resources,
what's your excuse?

I encourage everyone to fork [this](https://github.com/BartG95/BartG95) to their
[own GitHub profile](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).
Don't forget to change the name of the fork to your usename, and click the 'Share to Profile' button after forking.


[^1]: Which makes GitHub a single point of failure (and it indeed fails, on providing IPv6). Decentralize!
[^2]: The shortage of IPv4 makes it expensive, sometimes indirectly because you will have to work around (CG)NAT.
