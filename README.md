# elm-shrink

This is the shrinker used internally by elm-test. It is recommended that you don't use this implementation -- but if you need code similar to this, write your own. It will likely suit your performance needs better!

It is based on elm-lazy-list, which likewise has performance implications best suited for elm-test, and likely not suitable for other projects.