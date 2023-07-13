# Just Use the Source

<img src="./just_use_the_source.jpg">

Are you tired of [dependency
hell](https://en.wikipedia.org/wiki/Dependency_hell)? Are you tired of having to
import a library just to use a one-liner function? Do you wish you could just
share a piece of useful code simply and easily, without worrying about versions,
documentation, etc.? If so, you've come to the right place!

The purpose of this repository is to encourage the sharing and reuse of simple
pieces of code, without having to rely on complex infrastructure for managing
dependencies. The idea is really simple: for small(ish) pieces of code, that are
not expected to evolve in the future, it sometimes makes more sense to just copy
the code into your project, rather than include it as a dependency.

## Licensing

The "just use the source" ethic encourages, but does not mandate, the release of
code to the public domain. You might want to choose some other license that
better fits your needs and requirements. I am not a lawyer.

## How to Share Your Code

1. Put your amazingly useful code in a single file.
2. Include license information, and a repository URL in your code.
3. Add license information and adequate documentation.
4. Include a "Just use the source" comment in your code.
4. Publish your code on GitHub, GitLab or wherever.

Here's a sample source code file that follows the "just use the source" ethic:

```ruby
# This code is released to the public domain (2023).
# Author: Sharon Rosner
# https://github.com/digital-fabric/just-use-the-source
#
# Just use the source: copy this file into your project, and use it as you wish.

# Implements a greeter class
class Greeter
  # Initializes a greeter with the given name.
  #
  # @param name [String] name to be greeted
  def initialize(name)
    @name = name
  end

  # Prints a greeting to STDOUT
  #
  # @return [Greeter] self
  def greet
    puts "Hello, #{@name}!"
    self
  end
end
```

## How to Just Use the Source

1. Read the code and look for a "Just use the source" mention.
2. Make sure the license information meets your use case.
3. Copy the code into your project.
4. That's all there is to it.
