# lwt-pgocaml

Simple wrapper of [Lwt](http://ocsigen.org/lwt/) for use with [PG'OCaml](http://pgocaml.forge.ocamlcore.org/).

Use it like this:

    module PGOCaml = PGOCaml_generic.Make(Thread)

