# cargo doc

> Build and view Rust package documentation offline.

- Build and view the current packages documentation in your browser:

`cargo doc --open`

- View a particular packages documentation:

`cargo doc --open --package {{crate_name}}`

- View all workspace package documentation:

`cargo doc --open --workspace`

- Build documentation without accessing the network:

`cargo doc --offline`
