# Rust Web Frameworks

I compared some of the most popular rust web framework release build sizes by copy pasting 
Hello World -example codes from their documentation. 

Gotham had the smallest build size out of the box. It might have less features by default and could require more dependencies than the two others. 

Also Rocket framework uses nightly to compile.


## Running

Run ```cargo build --realease``` for each sub-project. And target/relase folders will show following:


## Results

```
# Gotham
2.5M Sep  3 21:35 gotham

# Warp
2.6M Sep  3 22:27 warp

# Rocket
4.2M Sep  3 21:40 rocket

# Actix-web
4.4M Sep  3 21:36 actix_web
```
