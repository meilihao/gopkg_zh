
| name / 名称   |  synopsis / 概述    |progress / 进度|
|--------------|:-------------------|--------------|
|archive|||
|[tar](pkgs/archive_tar.md)|Package tar implements access to tar archives.|0%|
|[zip](pkgs/archive_zip.md)|Package zip provides support for reading and writing ZIP archives.|0%|
|[bufio](pkgs/bufio.md)|Package bufio implements buffered I/O. It wraps an io.Reader or io.Writer object, creating another object (Reader or Writer) that also implements the interface but provides buffering and some help for textual I/O.|0%|
|[builtin](pkgs/builtin.md)|Package builtin provides documentation for Go's predeclared identifiers.|0%|
|[bytes](pkgs/bytes.md)|Package bytes implements functions for the manipulation of byte slices.|0%|
|compress|||
|[bzip2](pkgs/compress_bzip2.md)|Package bzip2 implements bzip2 decompression.|0%|
|[flate](pkgs/compress_flate.md)|Package flate implements the DEFLATE compressed data format, described in RFC 1951.|0%|
|[gzip](pkgs/compress_gzip.md)|Package gzip implements reading and writing of gzip format compressed files, as specified in RFC 1952.|0%|
|[lzw](pkgs/compress_lzw.md)|Package lzw implements the Lempel-Ziv-Welch compressed data format, described in T. A. Welch, “A Technique for High-Performance Data Compression”, Computer, 17(6) (June 1984), pp 8-19.|0%|
|[zlib](pkgs/compress_zlib.md)|Package zlib implements reading and writing of zlib format compressed data, as specified in RFC 1950.|0%|
|container|||
|[heap](pkgs/container_heap.md)|Package heap provides heap operations for any type that implements heap.Interface.|0%|
|[list](pkgs/container_list.md)|Package list implements a doubly linked list.|0%|
|[ring](pkgs/container_ring.md)|Package ring implements operations on circular lists.|0%|
|[context](pkgs/context.md)|Package context defines the Context type, which carries deadlines, cancellation signals, and other request-scoped values across API boundaries and between processes.|0%|
|[crypto](pkgs/crypto.md)|Package crypto collects common cryptographic constants.|0%|
|[aes](pkgs/crypto_aes.md)|Package aes implements AES encryption (formerly Rijndael), as defined in U.S. Federal Information Processing Standards Publication 197.|0%|
|[cipher](pkgs/crypto_cipher.md)|Package cipher implements standard block cipher modes that can be wrapped around low-level block cipher implementations.|0%|
|[des](pkgs/crypto_des.md)|Package des implements the Data Encryption Standard (DES) and the Triple Data Encryption Algorithm (TDEA) as defined in U.S. Federal Information Processing Standards Publication 46-3.|0%|
|[dsa](pkgs/crypto_dsa.md)|Package dsa implements the Digital Signature Algorithm, as defined in FIPS 186-3.|0%|
|[ecdsa](pkgs/crypto_ecdsa.md)|Package ecdsa implements the Elliptic Curve Digital Signature Algorithm, as defined in FIPS 186-3.|0%|
|[ed25519](pkgs/crypto_ed25519.md)|Package ed25519 implements the Ed25519 signature algorithm.|0%|
|[elliptic](pkgs/crypto_elliptic.md)|Package elliptic implements several standard elliptic curves over prime fields.|0%|
|[hmac](pkgs/crypto_hmac.md)|Package hmac implements the Keyed-Hash Message Authentication Code (HMAC) as defined in U.S. Federal Information Processing Standards Publication 198.|0%|
|[md5](pkgs/crypto_md5.md)|Package md5 implements the MD5 hash algorithm as defined in RFC 1321.|0%|
|[rand](pkgs/crypto_rand.md)|Package rand implements a cryptographically secure random number generator.|0%|
|~~[rc4](pkgs/crypto_rc4.md)~~|rc4包实现了RC4加密算法, 可参考Bruce Schneier的 *Applied Cryptography*||
|[rsa](pkgs/crypto_rsa.md)|Package rsa implements RSA encryption as specified in PKCS#1.|0%|
|[sha1](pkgs/crypto_sha1.md)|Package sha1 implements the SHA-1 hash algorithm as defined in RFC 3174.|0%|
|[sha256](pkgs/crypto_sha256.md)|Package sha256 implements the SHA224 and SHA256 hash algorithms as defined in FIPS 180-4.|0%|
|[sha512](pkgs/crypto_sha512.md)|Package sha512 implements the SHA-384, SHA-512, SHA-512/224, and SHA-512/256 hash algorithms as defined in FIPS 180-4.|0%|
|[subtle](pkgs/crypto_subtle.md)|Package subtle implements functions that are often useful in cryptographic code but require careful thought to use correctly.|0%|
|[tls](pkgs/crypto_tls.md)|Package tls partially implements TLS 1.2, as specified in RFC 5246, and TLS 1.3, as specified in RFC 8446.|0%|
|[x509](pkgs/crypto_x509.md)|Package x509 parses X.509-encoded keys and certificates.|0%|
|[pkix](pkgs/crypto_x509_pkix.md)|Package pkix contains shared, low level structures used for ASN.1 parsing and serialization of X.509 certificates, CRL and OCSP.|0%|
|database|||
|[sql](pkgs/database_sql.md)|Package sql provides a generic interface around SQL (or SQL-like) databases.|0%|
|[driver](pkgs/database_sql_driver.md)|Package driver defines interfaces to be implemented by database drivers as used by package sql.|0%|
|debug|||
|[dwarf](pkgs/debug_dwarf.md)|Package dwarf provides access to DWARF debugging information loaded from executable files, as defined in the DWARF 2.0 Standard at http://dwarfstd.org/doc/dwarf-2.0.0.pdf|0%|
|[elf](pkgs/debug_elf.md)|Package elf implements access to ELF object files.|0%|
|[gosym](pkgs/debug_gosym.md)|Package gosym implements access to the Go symbol and line number tables embedded in Go binaries generated by the gc compilers.|0%|
|[macho](pkgs/debug_macho.md)|Package macho implements access to Mach-O object files.|0%|
|[pe](pkgs/debug_pe.md)|Package pe implements access to PE (Microsoft Windows Portable Executable) files.|0%|
|[plan9obj](pkgs/debug_plan9obj.md)|Package plan9obj implements access to Plan 9 a.out object files.|0%|
|[encoding](pkgs/encoding.md)|Package encoding defines interfaces shared by other packages that convert data to and from byte-level and textual representations.|0%|
|[ascii85](pkgs/encoding_ascii85.md)|Package ascii85 implements the ascii85 data encoding as used in the btoa tool and Adobe's PostScript and PDF document formats.|0%|
|[asn1](pkgs/encoding_asn1.md)|Package asn1 implements parsing of DER-encoded ASN.1 data structures, as defined in ITU-T Rec X.690.|0%|
|[base32](pkgs/encoding_base32.md)|Package base32 implements base32 encoding as specified by RFC 4648.|0%|
|[base64](pkgs/encoding_base64.md)|Package base64 implements base64 encoding as specified by RFC 4648.|0%|
|[binary](pkgs/encoding_binary.md)|Package binary implements simple translation between numbers and byte sequences and encoding and decoding of varints.|0%|
|[csv](pkgs/encoding_csv.md)|Package csv reads and writes comma-separated values (CSV) files.|0%|
|[gob](pkgs/encoding_gob.md)|Package gob manages streams of gobs - binary values exchanged between an Encoder (transmitter) and a Decoder (receiver).|0%|
|[hex](pkgs/encoding_hex.md)|Package hex implements hexadecimal encoding and decoding.|0%|
|[json](pkgs/encoding_json.md)|Package json implements encoding and decoding of JSON as defined in RFC 7159.|0%|
|[pem](pkgs/encoding_pem.md)|Package pem implements the PEM data encoding, which originated in Privacy Enhanced Mail.|0%|
|[xml](pkgs/encoding_xml.md)|Package xml implements a simple XML 1.0 parser that understands XML name spaces.|0%|
|[errors](pkgs/errors.md)|errors包实现了用于处理错误的函数|0%|
|[expvar](pkgs/expvar.md)|Package expvar provides a standardized interface to public variables, such as operation counters in servers.|0%|
|[flag](pkgs/flag.md)|Package flag implements command-line flag parsing.|0%|
|[fmt](pkgs/fmt.md)|Package fmt implements formatted I/O with functions analogous to C's printf and scanf.|0%|
|go|||
|[ast](pkgs/go_ast.md)|Package ast declares the types used to represent syntax trees for Go packages.|0%|
|[build](pkgs/go_build.md)|Package build gathers information about Go packages.|0%|
|[constant](pkgs/go_constant.md)|Package constant implements Values representing untyped Go constants and their corresponding operations.|0%|
|[doc](pkgs/go_doc.md)|Package doc extracts source code documentation from a Go AST.|0%|
|[format](pkgs/go_format.md)|Package format implements standard formatting of Go source.|0%|
|[importer](pkgs/go_importer.md)|Package importer provides access to export data importers.|0%|
|[parser](pkgs/go_parser.md)|Package parser implements a parser for Go source files.|0%|
|[printer](pkgs/go_printer.md)|Package printer implements printing of AST nodes.|0%|
|[scanner](pkgs/go_scanner.md)|Package scanner implements a scanner for Go source text.|0%|
|[token](pkgs/go_token.md)|Package token defines constants representing the lexical tokens of the Go programming language and basic operations on tokens (printing, predicates).|0%|
|[types](pkgs/go_types.md)|Package types declares the data types and implements the algorithms for type-checking of Go packages.|0%|
|[hash](pkgs/hash.md)|Package hash provides interfaces for hash functions.|0%|
|[adler32](pkgs/hash_adler32.md)|Package adler32 implements the Adler-32 checksum.|0%|
|[crc32](pkgs/hash_crc32.md)|Package crc32 implements the 32-bit cyclic redundancy check, or CRC-32, checksum.|0%|
|[crc64](pkgs/hash_crc64.md)|Package crc64 implements the 64-bit cyclic redundancy check, or CRC-64, checksum.|0%|
|[fnv](pkgs/hash_fnv.md)|Package fnv implements FNV-1 and FNV-1a, non-cryptographic hash functions created by Glenn Fowler, Landon Curt Noll, and Phong Vo.|0%|
|[html](pkgs/html.md)|Package html provides functions for escaping and unescaping HTML text.|0%|
|[template](pkgs/html_template.md)|Package template (html/template) implements data-driven templates for generating HTML output safe against code injection.|0%|
|[image](pkgs/image.md)|Package image implements a basic 2-D image library.|0%|
|[color](pkgs/image_color.md)|Package color implements a basic color library.|0%|
|[palette](pkgs/image_color_palette.md)|Package palette provides standard color palettes.|0%|
|[draw](pkgs/image_draw.md)|Package draw provides image composition functions.|0%|
|[gif](pkgs/image_gif.md)|Package gif implements a GIF image decoder and encoder.|0%|
|[jpeg](pkgs/image_jpeg.md)|Package jpeg implements a JPEG image decoder and encoder.|0%|
|[png](pkgs/image_png.md)|Package png implements a PNG image decoder and encoder.|0%|
|index|||
|[suffixarray](pkgs/index_suffixarray.md)|Package suffixarray implements substring search in logarithmic time using an in-memory suffix array.|0%|
|[io](pkgs/io.md)|Package io provides basic interfaces to I/O primitives.|0%|
|[ioutil](pkgs/io_ioutil.md)|Package ioutil implements some I/O utility functions.|0%|
|[log](pkgs/log.md)|Package log implements a simple logging package.|0%|
|[syslog](pkgs/log_syslog.md)|Package syslog provides a simple interface to the system log service.|0%|
|[math](pkgs/math.md)|Package math provides basic constants and mathematical functions.|0%|
|[big](pkgs/math_big.md)|Package big implements arbitrary-precision arithmetic (big numbers).|0%|
|[bits](pkgs/math_bits.md)|Package bits implements bit counting and manipulation functions for the predeclared unsigned integer types.|0%|
|[cmplx](pkgs/math_cmplx.md)|Package cmplx provides basic constants and mathematical functions for complex numbers.|0%|
|[rand](pkgs/math_rand.md)|Package rand implements pseudo-random number generators.|0%|
|[mime](pkgs/mime.md)|Package mime implements parts of the MIME spec.|0%|
|[multipart](pkgs/mime_multipart.md)|Package multipart implements MIME multipart parsing, as defined in RFC 2046.|0%|
|[quotedprintable](pkgs/mime_quotedprintable.md)|Package quotedprintable implements quoted-printable encoding as specified by RFC 2045.|0%|
|[net](pkgs/net.md)|Package net provides a portable interface for network I/O, including TCP/IP, UDP, domain name resolution, and Unix domain sockets.|0%|
|[http](pkgs/net_http.md)|Package http provides HTTP client and server implementations.|0%|
|[cgi](pkgs/net_http_cgi.md)|Package cgi implements CGI (Common Gateway Interface) as specified in RFC 3875.|0%|
|[cookiejar](pkgs/net_http_cookiejar.md)|Package cookiejar implements an in-memory RFC 6265-compliant http.CookieJar.|0%|
|[fcgi](pkgs/net_http_fcgi.md)|Package fcgi implements the FastCGI protocol.|0%|
|[httptest](pkgs/net_http_httptest.md)|Package httptest provides utilities for HTTP testing.|0%|
|[httptrace](pkgs/net_http_httptrace.md)|Package httptrace provides mechanisms to trace the events within HTTP client requests.|0%|
|[httputil](pkgs/net_http_httputil.md)|Package httputil provides HTTP utility functions, complementing the more common ones in the net/http package.|0%|
|[pprof](pkgs/net_http_pprof.md)|Package pprof serves via its HTTP server runtime profiling data in the format expected by the pprof visualization tool.|0%|
|[mail](pkgs/net_mail.md)|Package mail implements parsing of mail messages.|0%|
|[rpc](pkgs/net_rpc.md)|Package rpc provides access to the exported methods of an object across a network or other I/O connection.|0%|
|[jsonrpc](pkgs/net_rpc_jsonrpc.md)|Package jsonrpc implements a JSON-RPC 1.0 ClientCodec and ServerCodec for the rpc package.|0%|
|[smtp](pkgs/net_smtp.md)|Package smtp implements the Simple Mail Transfer Protocol as defined in RFC 5321.|0%|
|[textproto](pkgs/net_textproto.md)|Package textproto implements generic support for text-based request/response protocols in the style of HTTP, NNTP, and SMTP.|0%|
|[url](pkgs/net_url.md)|Package url parses URLs and implements query escaping.|0%|
|[os](pkgs/os.md)|Package os provides a platform-independent interface to operating system functionality.|0%|
|[exec](pkgs/os_exec.md)|Package exec runs external commands.|0%|
|[signal](pkgs/os_signal.md)|Package signal implements access to incoming signals.|0%|
|[user](pkgs/os_user.md)|Package user allows user account lookups by name or id.|0%|
|[path](pkgs/path.md)|Package path implements utility routines for manipulating slash-separated paths.|0%|
|[filepath](pkgs/path_filepath.md)|Package filepath implements utility routines for manipulating filename paths in a way compatible with the target operating system-defined file paths.|0%|
|[plugin](pkgs/plugin.md)|Package plugin implements loading and symbol resolution of Go plugins.|0%|
|[reflect](pkgs/reflect.md)|Package reflect implements run-time reflection, allowing a program to manipulate objects with arbitrary types.|0%|
|[regexp](pkgs/regexp.md)|Package regexp implements regular expression search.|0%|
|[syntax](pkgs/regexp_syntax.md)|Package syntax parses regular expressions into parse trees and compiles parse trees into programs.|0%|
|[runtime](pkgs/runtime.md)|Package runtime contains operations that interact with Go's runtime system, such as functions to control goroutines.|0%|
|[cgo](pkgs/runtime_cgo.md)|Package cgo contains runtime support for code generated by the cgo tool.|0%|
|[debug](pkgs/runtime_debug.md)|Package debug contains facilities for programs to debug themselves while they are running.|0%|
|msan|||
|[pprof](pkgs/runtime_pprof.md)|Package pprof writes runtime profiling data in the format expected by the pprof visualization tool.|0%|
|[race](pkgs/runtime_race.md)|Package race implements data race detection logic.|0%|
|[trace](pkgs/runtime_trace.md)|Package trace contains facilities for programs to generate traces for the Go execution tracer.|0%|
|[sort](pkgs/sort.md)|Package sort provides primitives for sorting slices and user-defined collections.|0%|
|[strconv](pkgs/strconv.md)|Package strconv implements conversions to and from string representations of basic data types.|0%|
|[strings](pkgs/strings.md)|Package strings implements simple functions to manipulate UTF-8 encoded strings.|0%|
|[sync](pkgs/sync.md)|Package sync provides basic synchronization primitives such as mutual exclusion locks.|0%|
|[atomic](pkgs/sync_atomic.md)|Package atomic provides low-level atomic memory primitives useful for implementing synchronization algorithms.|0%|
|[syscall](pkgs/syscall.md)|Package syscall contains an interface to the low-level operating system primitives.|0%|
|[js](pkgs/syscall_js.md)|Package js gives access to the WebAssembly host environment when using the js/wasm architecture.|0%|
|[testing](pkgs/testing.md)|Package testing provides support for automated testing of Go packages.|0%|
|[iotest](pkgs/testing_iotest.md)|Package iotest implements Readers and Writers useful mainly for testing.|0%|
|[quick](pkgs/testing_quick.md)|Package quick implements utility functions to help with black box testing.|0%|
|text|||
|[scanner](pkgs/text_scanner.md)|Package scanner provides a scanner and tokenizer for UTF-8-encoded text.|0%|
|[tabwriter](pkgs/text_tabwriter.md)|Package tabwriter implements a write filter (tabwriter.Writer) that translates tabbed columns in input into properly aligned text.|0%|
|[template](pkgs/text_template.md)|Package template implements data-driven templates for generating textual output.|0%|
|[parse](pkgs/text_template_parse.md)|Package parse builds parse trees for templates as defined by text/template and html/template.|0%|
|[time](pkgs/time.md)|Package time provides functionality for measuring and displaying time.|0%|
|[unicode](pkgs/unicode.md)|Package unicode provides data and functions to test some properties of Unicode code points.|0%|
|[utf16](pkgs/unicode_utf16.md)|Package utf16 implements encoding and decoding of UTF-16 sequences.|0%|
|[utf8](pkgs/unicode_utf8.md)|Package utf8 implements functions and constants to support text encoded in UTF-8.|0%|
|[unsafe](pkgs/unsafe.md)|Package unsafe contains operations that step around the type safety of Go programs.|0%|