# kiss-repos

What is this?

> This is a collection of kiss-repos that are meant to be easily added/used
> by using git submodules. Each repo is limited in scope and of high quality.

Why is this?

> I think that it will be easier to have more up to date packages for many
> people if repos are done via modules, thus allowing for easy maintenance
> from all parties.

The packages in the repos are as all encompassing as they can be, requiring
no hard dependencies, yet allowing for many optional dependencies. This is
so that other package mantainers can *enforce* those hard dependencies in their
own repos, but without having to actually maintain the build script and
versioning information.

Additionally, the hope is that by having all of these packages be available,
more people may be inclined to port more software over to kiss.

**NOTE:** I'd be happy to move these repos to a more public location, such
as https://github.com/kiss-community or https://codeberg.org/kiss-community

## current repos

* `gnome/` - contains software distributed by gnome.org & deps

* `freedesktop/` - contains software distributed by freedesktop.org & deps

* `python/` - contains misc. python packages.

* `qt-toolkit/` - contains qt5 & friends. Soon to contain qt6 aswell.
