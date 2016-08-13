# wifiscanner

A crate to list WiFi hotspots in your area.

As of v0.3.0 now supports OSX and Linux. Windows to
follow.

Inspired by Maurice Svay's node-wifiscanner (https://github.com/mauricesvay/node-wifiscanner)

Tests shameless pilfered from Christian Kuster's node-wifi-scanner (https://github.com/ancasicolica/node-wifi-scanner)

# Usage

This crate is [on crates.io](https://crates.io/crates/wifiscanner) and can be
used by adding `wifiscanner` to the dependencies in your project's `Cargo.toml`.

```toml
[dependencies]
wifiscanner = "0.3"
```

and this to your crate root:

```rust
extern crate wifiscanner;
```
# Example

```rust
use wifiscanner;
println!("{:?}", wifiscanner::scan());
```

# Copyright

Copyright 2016 Mark Sta Ana.

Licensed under the Apache License, Version 2.0 <LICENSE-APACHE or
http://www.apache.org/licenses/LICENSE-2.0> at your option. This file may not
be copied, modified, or distributed except according to those terms.
