# weatherspect-brew

(Unofficial) homebrew formula for Weatherspect

Weatherspect code can be found here: https://robobunny.com/projects/weatherspect/html/

Credit to Kirk Baucom https://robobunny.com

### How to use

Requires homebrew to be previously installed: https://brew.sh

Add formula to (local) homebrew:

```cp weatherspect.rb /opt/homebrew/Library/Taps/homebrew/homebrew-core/Formula/weatherspect.rb```

Install formula:

```brew install --build-from-source weatherspect```

Create config file:

```weatherspect -c```

Run weatherspect:

```weatherspect```
