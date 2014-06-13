Cookbook to connect Redis to rails
==================================

This is used to generate a redis config for rails.

TODO
====
Because cloud formation doesn't support ConfigurationEndpoint.Address
and ConfigurationEndpoint.Port on redis clusters, we can't give them
directly. We need to figure out how to call aws-sdk from this cookbook
to find endpoint for redis from cluster name.

Look at deploy[:redis][:cluster] to find cluster name.
