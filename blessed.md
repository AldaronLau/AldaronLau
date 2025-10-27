# Blessed

This blessed list contains crates I prefer, and crates I made, and some mentions
of alternatives.  Crates I made are listed with 🩷.  To be a crate that I
prefer, it must be something that I would be happy with the design if I were to
develop it by myself (pretty strict).

# Stable Crates (>= 1.0.0)

## Rust Patterns

### [`specializer`](https://docs.rs/specializer) 🩷

 - Specialize on specific types in generic contexts using the builder pattern
   (specialization)

### [`as_repr`](https://docs.rs/as_repr) 🩷

 - Generic safe transmutes in `const` contexts

## Computer Information

### [`whoami`](https://docs.rs/whoami) 🩷

 - Get username, full name, hostname, computer display name, user preferred
   languages, desktop environment, OS version

## Parsing

### [`data-encoding`](https://docs.rs/data-encoding)

 - Encode/decode base64, base32, and hex

### [`bytemuck`](https://docs.rs/bytemuck)

 - Casting of "plain data" (no invalid bit patterns nor special invariants)

## Terminal I/O

### [`yansi`](https://docs.rs/yansi)

 - ANSI terminal color painting library

## Graphics

### [`wgpu`](https://docs.rs/wgpu)

 - A cross-platform graphics and compute library based on WebGPU

## Web

### [`webbrowser`](https://docs.rs/webbrowser)

 - Open URLS in a web browser

# Unstable Crates (< 1.0.0)

## Web

### [`rookie`](https://docs.rs/rookie)

 - Load web browser cookies

## HTML

### [`hatmil`](https://docs.rs/hatmil)

 - HTML generation

## Video

### [`pix`](https://docs.rs/pix)

 - Image raster/ pixel format newtypes and coversions

## Parsing

### [`gift`](https://docs.rs/gif)

 - GIF encoding / decoding

### [`png_pong`](https://docs.rs/png_pong) 🩷

 - PNG encoding / decoding

## Audio

### [`fon`](https://docs.rs/fon) 🩷

 - Audio buffer format newtypes and conversions

### [`wavy`](https://docs.rs/wavy) 🩷

 - Audio recording and playback

### [`twang`](https://docs.rs/twang) 🩷

 - Audio synthesis

## Multimedia

### [`p-chan`](https://docs.rs/p-chan) 🩷

 - Multimedia format newtypes and conversions

## Async

### [`pasts`](https://docs.rs/pasts) 🩷

 - Async executor

### [`event_iterator`](https://docs.rs/event_iterator) 🩷

 - Lending async iteration
