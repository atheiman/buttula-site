[gh-pages branch hosted for free using GitHub Pages](http://atheiman.github.io/buttula-site/)

## Technical Explanation

Hosting is setup at bluehost.com. [Login](https://my.bluehost.com/web-hosting/cplogin) with the domain name (`bbqbuttula.com`) and the password.

Hosting at bluehost.com is not needed. [GitHub](https://github.com) (this site) provides free static web site hosting. GitHub's main role is a version control system. It is a place for software developers to share their code. The site is automatically created at http://atheiman.github.io/buttula-site/ whenever the code is updated. That URL looks ugly though.

So I have pointed the domain bbqbuttula.com to atheiman.github.io/buttula-site. This is accomplished by creating an A record in the [DNS Zone Editor on bluehost.com](https://my.bluehost.com/cgi/dm/zoneedit) pointing bbqbuttula.com to GitHub IP addresses as described [here](https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider/#configuring-an-a-record-with-your-dns-provider) You can access the site from either URL and the same content is returned, but the point is bbqbuttula.com looks a lot better and is easier to sell atheiman.github.io/buttula-site.
