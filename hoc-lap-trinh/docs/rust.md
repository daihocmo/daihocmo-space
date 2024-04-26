Khóa học này được làm cho chính mình, một người đang học Rust tính đến thời điểm hiện tại

Let's start there.
[https://rustup.rs](https://rustup.rs/)

notes:

If you're on mac or linux or WSL, run this command in a terminal.

If you're on windows and can't run WSL, then download and run the installer, probably the 64-bit version.

Linux is the native operating system of the internet, and I would recommend that windows users install Microsoft's Windows Subsystem for Linux, WSL, to get access to this incredible world.

Next you need the core triumvirate that is required learning for my students

notes:

The three pillars of my recommended syllabus are:

1. [The Rust Programming language book](https://doc.rust-lang.org/stable/book/), which from now on we just call The Book
2. [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/), excellent supplementary reading, and
3. [Rustlings](https://github.com/rust-lang/rustlings), an interactive code kata system, one of the best I've ever used.

Though there are many other great ways to learn Rust, I recommend starting with these three because they are so tightly bound together, in a way that you might have missed.


### SIDE QUEST #1

This is Ultralearning by Scott H Young. (not sponsored) A very good book on the meta process of learning to learn.

You should read it, or listen to it on audiobook as I did.


In Chapter 8 Young highlights a study where it seemed that students who took the exam and failed BEFORE studying did far better than those who only studied and then took the exam.

He calls this procedure "Test to Learn", and it makes a lot of sense.

It's like placing a number of boxes in your mind, labelled with the information you would LIKE to be there, facts, figures, how lifetime annotations work, etc. Then when you are studying later, you more readily absorb the information because you are already looking for it.

Keep this in mind when I tell you my next tip:

### Side quest #2


# Read the book twice

(second time: [https://rust-book.cs.brown.edu](https://rust-book.cs.brown.edu/))

notes:

I recommend reading the rust book from cover to cover as fast as possible, and without stopping to do the exercises. If you come across something you don't understand, mentally note it, and move on to the next chapter. The point is to pass the words through you eyeball compiler, and not worry too much about how many errors you get.

Then when you have finished, go back to the start and work through at your normal pace, but read the Brown University version with interactive quizzes.

- [x]  re-record this take and use the new slide

You can now install Rustlings.


## [rust-lang/Rustlings](https://github.com/rust-lang/rustlings)

```shell
curl -L https://raw.githubusercontent.com
/rust-lang/rustlings/main/install.sh | bash
```

Here is the first exercise, fixing a hello world.

Rustlings starts out extremely simply, and ramps up slowly. Even non-programmers could start this way, and veterans will speed through the early questions quickly.

Though starting simple, they follow the book all the way through lifetimes, smart pointers, and threads.

Note that the rustlings watcher, the output of which we are seeing here, has some extra functionality, not just auto-refreshing output from the compiler.

Each exercise has a hint, accessed by simply typing hint into the watcher, as I did here.

---
notes:

Rustlings exercises are katas.

Katas, a term borrowed from Japanese martial arts, are something you practice over and over again, to build muscle memory. Musicians do the same thing.

At time of writing there are 95 Rustlings katas, when you have done them all, it is time to choose your favourites to re-do regularly. I recommend weekly.

Keep your muscle memory fresh.



### Các nguồn học sau đó trên Youtube
In order:

1. The official Rust book. Practise with rustlings.
    
2. Programming Rust by Jim Blandy et al.
    
3. Small hobby projects.
    
4. Rust for Rustaceans by Gjengset.
    
5. Bigger, more complex projects. Experiment with common crates - tokio, serde, sqlx, thiserror, anyhow, axum etc.
    
6. Common Rust lifetime misconceptions (~~Google it~~[https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md)).
    
7. Implementing too many lists in Rust (~~Google it~~[https://rust-unofficial.github.io/too-many-lists/](https://rust-unofficial.github.io/too-many-lists/)).
    
8. Full-fledged projects, open source contributions etc.


### Danh sách khác

Here are the ones that I know of:

- [Rust Videos](https://www.youtube.com/@RustVideos) Video material about the programming language Rust, curated by the Rust team. This channel publishes videos from all Rust conferences and also re-publish talks and lectures from other places. [RustConf 2023 Playlist](https://www.youtube.com/watch?v=MTnIexTt9Dk&list=PL85XCvVPmGQgR1aCC-b0xx7sidGfopjCj)
    
- [Jon Gjengset](https://www.youtube.com/@jonhoo) ouputs truly top-tier content for intermediate and beyond. The [Crust of Rust](https://www.youtube.com/playlist?list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa) series is phenomenal learning material.
    
- [fasterthanlime](https://www.youtube.com/@fasterthanlime) does some incredibly deep dives into really interesting topics. While his content is always stellar, it is not exactly geared toward beginner or journeyman level
    
- [Chris Biscardi](https://www.youtube.com/@chrisbiscardi) covers a pretty wide range of rust-related topics, from version releases to general topics to WASM
    
- [Code To The Moon](https://www.youtube.com/@codetothemoon) has some really good rust-related videos, some for niche applications (e.g. ML, WASM)
    
- [No Boilerplate](https://www.youtube.com/@NoBoilerplate) Has some good rust specific content in a fast format.
    
- [Doug Milford](https://www.youtube.com/watch?v=Az3jBd4xdF4&list=PLLqEtX6ql2EyPAZ1M2_C0GgVd4A-_L4_5) has a pretty comprehensive tutorial series on rust
    
- [strager](https://www.youtube.com/@strager_) covers some interesting topics, like implementing a perfect hash function.
    
- [Let's Get Rusty](https://www.youtube.com/@letsgetrusty) goes through _The Book_ chapter by chapter. He has other rust content as well.
    
- [Trevor Sullivan](https://www.youtube.com/@TrevorSullivan) Has a lot of quality tutorials and videos on rust.
    

---

Additions from [GreatSt](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq4770f), [Pure_Squirrel175](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq4ahg1/), [IsotoxalDev](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq4be5v), [half-villain](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq4dqmo/), [TheZagitta](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq4qg95), [careyi4](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq5568g), [AmeKnite](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq6axf2), [Dhghomon](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq6psfx), [SalesyMcSellerson](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq8084q/), [DavidXkL](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq7yv20/), [1668553684](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq6tadn/), [nameEqualsJared](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq62zcu/), [Party-Performance-82](https://www.reddit.com/r/rust/comments/1ap65vd/comment/kq8xsuq/), [Ludo_Tech](https://www.reddit.com/r/learnrust/comments/1apvwl1/comment/kq9bren/), [Siallus](https://www.reddit.com/r/learnrust/comments/1apvwl1/comment/kqbibv7/), [Immediate-Hold-7163](https://www.reddit.com/r/learnrust/comments/1apvwl1/comment/kqte3f1), and me:

- [Jeremy Chone](https://www.youtube.com/@JeremyChone) "Channel focused on Rust Programming Language and Scaling Code for Cloud Application Development."
    
- [You Code Things](https://www.youtube.com/@YouCodeThings) "Making programming videos for you."
    
- [Logan Smith](https://www.youtube.com/@_noisecode) "I'm Logan. I love computer programming and learning new stuff. Come hang out and geek out with me."
    
- [Low Level Learning](https://www.youtube.com/@LowLevelLearning) "Teaching you 🧠 about the lowest level"
    
- [Tom McGurl](https://www.youtube.com/@TomMcGurl/videos) "I'm a Software Engineer who loves sharing my latest experiments with others"
    
- [TanTan](https://www.youtube.com/@Tantandev) "game developer currently utilizing the rust programming language."
    
- [Tsoding](https://www.youtube.com/@TsodingDaily) "'Daily' Development Log of Tsoding"
    
- [Copenhagen Rust Community](http://www.youtube.com/@copenhagenrustcommunity) Video archive of past meetups from the Copenhagen Rust Community with excellent talks from people like Jon Gjenset, Alice Ryhl (tokio), David Pedersen (axum) and Rob Ede (actix)
    
- [Rust Nederland (RustNL)](https://www.youtube.com/@rustnederlandrustnl) Rust NL organizes meetups (talks and workshops) about Rust, the programming language that empowers everyone to build reliable and efficient software.
    
- [Ian Carey](https://www.youtube.com/@careyian) with a focus is on hardware / embedded which seems uncommon so far.
    
- [mithradates](https://www.youtube.com/watch?v=-lYeJeQ11OI&list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk) Easy Rust, also available in Korean
    
- [Logic Projects](https://www.youtube.com/@logicprojects) "Creating educational tutorials about the Bevy game engine in Rust!"
    
- [Michael Mullin](https://www.youtube.com/@masmullin) Has videos on some intriguing (rust) topics
    
- [WhiteSponge](https://www.youtube.com/@WhiteSponge) "Sharing the love for all things technology, design and coding related!"
    
- [Ryan Levick](https://www.youtube.com/channel/UCpeX4D-ArTrsqvhLapAHprQ) "A place for learning about Rust! 🦀 Content ranges from beginner to advanced so there should be something for everyone!"
    
- [Sreekanth](https://www.youtube.com/watch?v=7_o-YRxf_cc) Only has 1 rust related video so far but it is quite good!
    
- [Zymartu Games](https://www.youtube.com/@ZymartuGames) "Crafting games and sharing Bevy knowledge. Stay tuned for our game and tutorials!"
    
- [Rust and C++ Cardiff Meetup](https://www.youtube.com/@rustandcppcardiffmeetup4173/) "Rust and C++ Cardiff is a meetup group for high performance programming language enthusiasts - beginners and seasoned developers from all fields." It has a [full series based on The Book](https://www.youtube.com/playlist?list=PL8AZrEE2-qZkcOFmpC03TwnVHSr25luFp), and just started another one with "Rust for Rustaceans".
    
- [Green Tea Coding](https://www.youtube.com/@GreenTeaCoding) "Hi, I am Max, and I teach coding in a relaxed, stress-free way. The focus of my weekly videos is on building an understanding for the fundamentals of Rust"
    
- [yishn](https://www.youtube.com/playlist?list=PLtTT8p-gjGEdGzZ0ET2bwNnA6iP_mmmrv) has a Lets Code playlist on Rust + WASM
    
- [Tech with Tim](https://www.youtube.com/watch?v=T_KrYLW4jw8&list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ) has a Rust tutorial series
    
- [Vandad Nahavandipoor](https://www.youtube.com/playlist?list=PL6yRaaP0WPkWRsXJgdnw9lj1vchAaKwfS) has a course on rust that is very fast paced and designed for programmers who already have some experience with another programming language
    
- [freeCodeCamp.org](https://www.youtube.com/watch?v=BpPEoZW5IiY) has a complete course on rust available.
    
- [Microsoft Developer](https://www.youtube.com/playlist?list=PLlrxD0HtieHjbTjrchBwOVks_sr8EVW1x) has a 35-video playlist for beginners
