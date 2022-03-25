# go-authcrunch

AuthCrunch provides Authentication, Authorization, and Accounting (AAA)
Security Functions (SF) in Golang.

<a href="https://github.com/toowoxx/go-authcrunch/actions/" target="_blank"><img src="https://github.com/toowoxx/go-authcrunch/workflows/build/badge.svg?branch=main"></a>
<a href="https://pkg.go.dev/github.com/toowoxx/go-authcrunch" target="_blank"><img src="https://img.shields.io/badge/godoc-reference-blue.svg"></a>

This code base contains the functions implementing AAA. It is a
standalone library, i.e. it can be used with Gin, Beego, Echo,
Mux (Gorilla). Originally, the library was a part of the development
of Caddy v2 `caddy-auth-portal`, `caddy-auth-jwt`, and
`caddy-authorize` plugins.

**Important:**
This project is a fork of https://github.com/greenpau/go-authcrunch.
If you want to use it, you need to add a replace line to your go.mod like so:

```
replace github.com/greenpau/go-authcrunch <version> => github.com/toowoxx/go-authcrunch <version>
```

We may change this in the future but for now we'll keep the original module name to ease upstream merges.

**Documentation**: [authp.github.io](https://authp.github.io/)

**Issues**:

* Caddy-specific: [Open](https://github.com/toowoxx/caddy-security/issues/new/choose)
* Other Go-frameworks: [Open](https://github.com/toowoxx/go-authcrunch/issues/new/choose)

## License

See [LICENSE](./LICENSE)

```
   Copyright 2022 Paul Greenberg (@greenpau)
   Copyright 2022 Toowoxx IT GmbH

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
