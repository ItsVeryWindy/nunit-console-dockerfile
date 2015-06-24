# Supported tags and `Dockerfile` links

- [`latest` (*Dockerfile*)](https://github.com/ItsVeryWindy/nunit-console/2.6.4/Dockerfile)
- [`2.6.4` (*Dockerfile*)](https://github.com/ItsVeryWindy/nunit-console/2.6.4/Dockerfile)

# What is nunit-console

nunit-console is part of the [NUnit unit-testing framework](http://www.nunit.org/), it allows you to run your unit tests from the command line as seen [here](http://www.nunit.org/index.php?p=nunit-console&r=2.6.4).

# How to use this image
This image features an entrypoint for nunit-console. Attach a volume containing assemblies and set it as the working directory.
    
    docker run -v /path/to/assemblies --workdir /path/to/assembles itsverywindy/nunit-console [nunit console arguments]

# Issues

Please report issues on the [GitHub project](https://github.com/ItsVeryWindy/nunit-console-dockerfile).
