URL Block Plugin for Mecha
==========================

Support these block patterns:

 - `[‌[‌url‌]‌]` → `http://localhost/a`
 - `[‌[‌url.scheme]‌]` → `http`
 - `[‌[‌url.protocol‌]‌]` → `http://`
 - `[‌[‌url.host‌]‌]` → `localhost`
 - `[‌[‌url.port‌]‌]` → `80`
 - `[‌[‌url.directory‌]‌]` → `a`
 - `[‌[‌url.url‌]‌]` → same as `[‌[‌url‌]‌]`
 - `[‌[‌url.path‌]‌]` → `foo/bar`
 - `[‌[‌url.query‌]‌]` → `?foo=bar&baz=qux`
 - `[‌[‌url.current‌]‌]` → `http://localhost/a/foo/bar`

### Dependency

 - **Extension**
   - Block