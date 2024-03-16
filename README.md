# OpenSourceContributions
My open-source project contributions.

- 2011 (Java Netty): [Contributed failImmediatelyOnTooLongFrame option to Netty decoders](https://github.com/netty/netty/pull/25)
  - These options [still](https://github.com/netty/netty/blob/4.1/codec/src/main/java/io/netty/handler/codec/DelimiterBasedFrameDecoder.java#L67) [exist](https://github.com/netty/netty/blob/4.1/codec/src/main/java/io/netty/handler/codec/LengthFieldBasedFrameDecoder.java#L196) in Netty
  - Options been renamed to better name [`failFast`](https://github.com/netty/netty/commit/0850449b096218c1bf1c5de5e9603ff490f8efcb) which is a good move in retrospect :)
- 2011 (C++ boost): [Contributed lock-free version](https://lists.boost.org/boost-bugs/2011/12/20673.php) of `boost::shared_ptr` for IBM AIX operating system to improve performance.
  - [`boost::shared_ptr`](https://theboostcpplibraries.com/boost.smartpointers-shared-ownership) is reference-counted, thread-safe smart pointer similar to [Arc in Rust](https://doc.rust-lang.org/std/sync/struct.Arc.html).
  - My code [still exists in the boost source code](https://github.com/boostorg/smart_ptr/blob/develop/include/boost/smart_ptr/detail/sp_counted_base_aix.hpp).
  - Eventually `boost::shared_ptr` became [`std::shared_ptr`](https://en.cppreference.com/w/cpp/memory/shared_ptr) in c++11.
