rust-nanomsg
============

Summary: nanomsg bindings for rust

rust: http://www.rust-lang.org/
      https://github.com/mozilla/rust

nanomsg: http://nanomsg.org/
         https://github.com/nanomsg/nanomsg

Rust is a modern langauge from Mozilla Research. It has  support for 
 writing embedded applications that are memory safe and simultaneously
 do not suffer garbage-collection pauses. license: dual MIT / Apache 2.

 You'll want the github MASTER branch of rust to do anything useful
 and up to date. The project has strong velocity, so it is evolving
 quickly.

nanomsg is a modern messaging library that is the 
 successor to ZeroMQ, written in C by Martin Sustrik and colleagues.
 The nanomsg library is licensed under MIT/X11 license. "nanomsg" 
 is a trademark of 250bpm s.r.o.  I'm using the HEAD of the

       * master 244540c changed location of the repo reflected in README

 branch for nanomsg.



These rust-nanogen bindings were initiated using an automated bindings
 generator called rust-bindgen from Jyun-Yan You (repository:
 https://github.com/crabtw/rust-bindgen ) and then hand edited to
 include necessary pub static constants extracted manually. The
 later process involved using the cpp -dD flag to extract #defines,
 and rewriting them as "pub static MYCONST: int = 1;" statements.


Status:  in development. 