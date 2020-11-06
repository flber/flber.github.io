### Learning Rust

First of all, this is going to primarily a place to store notes for myself as I learn Rust, so take everything I say with a grain of salt! (though feedback is always appreciated, so feel free to say hi)

Good resources:
- [[Simple Rust GUI with QML]](https://www.vandenoever.info/blog/2017/02/17/a-simple-rust-gui-with-qml.html)
- [[Rust Programming Tutorial]](https://www.youtube.com/playlist?list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL)

Things to remember:
- variables need the `mut` tag to be changeable
- it's statically typed!
- tuples can hold different types, arrays cannot
- most names should be in `snake_case`
- types, enums, and traits should be in `CamelCase`
- anything static should be in `SCREAMING_SNAKE_CASE`
- if it looks like a function but has a `!` at the end, it's a macro (?? what's a macro ??)
- `&` means a reference to an object?
- `.expect()` is used to handle possible errors
- `::` refers to an associated function of a "type" (static method)
- references are immutable by default

Things I'm not sure about
- macros
- passing objects by reference
- `#[]` <- these things
- what is a type?