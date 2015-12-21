# NAME

Test2 - Framework for writing test tools that all work together.

# EXPERIMENTAL RELEASE

This is an experimental release. Using this right now is not recommended.

# DESCRIPTION

Test2 is a new testing framework produced by forking [Test::Builder](https://metacpan.org/pod/Test::Builder),
completely refactoring it, adding many new features and capabilities.

# GETTING STARTED

If you are interested in writing tests using new tools then you should look at
**NOT YET DETERMINED**.

If you are interested in writing new tools you should take a look at
[Test2::API](https://metacpan.org/pod/Test2::API) first.

# SEE ALSO

[Test2::API](https://metacpan.org/pod/Test2::API) - Primary API functions.

[Test2::Context](https://metacpan.org/pod/Test2::Context) - Detailed documentation of the context object.

[Test2::Global](https://metacpan.org/pod/Test2::Global) - Interface to global state. This is where to look if you need
a tool to produce a global effect.

[Test2::IPC](https://metacpan.org/pod/Test2::IPC) - The IPC system used for threading/fork support.

[Test2::Formatter](https://metacpan.org/pod/Test2::Formatter) - Formatters such as TAP live here.

[Test2::Event](https://metacpan.org/pod/Test2::Event) - Events live in this namespace.

[Test2::Hub](https://metacpan.org/pod/Test2::Hub) - All events eventually funnel through a hub. Custom hubs are how
`intercept()` and `run_subtest()` are implemented.

# SOURCE

The source code repository for Test2 can be found at
`http://github.com/Test-More/Test2/`.

# MAINTAINERS

- Chad Granum &lt;exodist@cpan.org>

# AUTHORS

- Chad Granum &lt;exodist@cpan.org>

# COPYRIGHT

Copyright 2015 Chad Granum &lt;exodist7@gmail.com>.

This program is free software; you can redistribute it and/or
modify it under the same terms as Perl itself.

See `http://dev.perl.org/licenses/`