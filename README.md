BeSport Platform Dependencies
=============================

These dependencies are required by the BeSport platform, but we put them here for anyone to use.

To install them :

   * Setup the BeSport tap (ignore any warnings about already-existing ocaml)

         brew tap besport/ocaml

   * Install OCaml from source (we still need a special patch for things to work correctly)

         brew install --source besport/ocaml/objective-caml
    
   * Install Dependencies

         brew install ocaml-aws ocaml-calendar ocaml-camlzip ocaml-cppo ocaml-cryptokit ocaml-data-notation ocaml-deriving ocaml-easy-format ocaml-eliom ocaml-ev ocaml-findlib ocaml-imagemagick ocaml-jsofocaml ocaml-leveldb ocaml-lwt ocaml-net ocaml-oasis ocaml-pcre ocaml-aliases ocaml-react ocaml-sqlite3 ocaml-ssl ocaml-typeconv ocaml-tyxml ocaml-xmlm ocaml-yojson ocamlify ocamlmod ocaml-biniou ocaml-ocsigenserver
