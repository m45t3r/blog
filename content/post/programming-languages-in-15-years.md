+++
author = "Thiago Kenji Okada"
date = "2017-04-07T20:32:25-03:00"
description = "What will happen in todays' most popular programming languages in 15 years?"
tags = ["dev"]
title = "Programming Languages in 15 years"

+++

This is a post that I wanted to write for a long time. The idea is to imagine how popular todays' most popular programming languages will be in **15 years**.

*15 years* was chosen because it is quite a nice period of time: *10 years* would be too soon so that the programming landscape wouldn't change too much from what it is nowadays. *20 years* is too long of a period to make any kind of precise foresight. Not that this post will necessary be precise, since I can be completely wrong and COBOL will be great again!

To start, I want to define a popularity score that will be used in this post. They will make it clear how popular I think a language will popular in the future by comparing the popularity of some of todays language:

- **0 - Death**: it is difficult to really kill a programming language. If there is a working compiler/interpreter or at least the language specification somewhere (so someone can write a working compiler), it means someone can write a new software for it, even if it means only for amusement. So what **death** means? It means that you don't hear people writting code on it, except maybe for an obscure post on some obscure blog. For example, today languages that can be considered death is: Algol, APL or ML. If **death** is still not clear, the next score will probably makes thinks more clear.

- **1 - COBOL-like popularity**: COBOL-like is really about being what COBOL is today: nobody wants to create a new system in COBOL, yet there are still tons of systems that was written in this language that needs to be maintained. So, a *COBOL-like* classification is a programming language mostly in maintance state, not having any new or relevant development. Today examples: COBOL (of course), Delphi or ADA.

- **2 - Declining popularity**: a language that is still popular, and people still write new software. However, ask devs the language they want to write new projects in, and they probably will avoid to cite those languages. In resume, the popularity is decreasing and the language is (slowly) dying. Today examples: Perl.

- **3 - Stable popularity**: a language that popularity is relatively stable. It is not increasing, it is not decreasing, it is just stable. C is probably the best example here, even if it also fit a score 5 considering that is one of the most popular language nowadays.

- **4 - HN-level popularity**: so [Hacker News](https://news.ycombinator.com/) may not exist in 15 years. However, there will be a popular news site (like [Slashdot](https://slashdot.org/) before and HN nowadays) and this will be the kind of language that everybody is talking about, however not necessary programming on it. The language popularity is basically increasing each day. Today examples: Go, Rust, Kotlin.

- **5 - TIOBE-Index popularity**: same thing as above, maybe in 15 years [TIOBE-index](https://www.tiobe.com/tiobe-index/) may not exist anymore. However, there will be some kind of popularity index equivalent of todays TIOBE-index, so any language that has potential to appear (or stay) as the ~20 most popular languages in the world will receive a score of 5. Today examples: Java, C, C++, C#, Python, Javascript, etc.

Before starting to read, remember: this post is only for fun. Don't start to panic if I say that your favorite language will be in a COBOL-like state in 15 years. This is simple a imagination excercise and I may be **completely** wrong. However, maybe, just maybe, I will be right in some of these foresights. Another note: I tried to put similar languages near each orher, so the order may seem somewhat random.

So lets start!

## Ruby

**Score: 1-2**

Thinking about the future of Ruby is actually what made me write this post, so except lots of comparison with Ruby (specially because I think this is the most controversial part of this post).

Ruby nowadays, even if is sufficiently popular to receive a score of 5 today ([#12 in TIOBE-Index](https://www.tiobe.com/tiobe-index/ruby/)), is dying. It is not difficult to understand why: the language was amazing popular in 2010's thanks to the popularity of [Ruby on Rails](http://rubyonrails.org/). Thanks to this popularity, the Ruby language become wildly popular for Web development, and the whole Ruby ecosystem evolved around Web development. However, the language did not expand in other niches, and other languages started to get good for Web development, having frameworks copying the good parts of RoR (MVC, TDD, ActiveRecord, etc.). This bring us today, where you see the popularity of Ruby decreasing in each new release of TIOBE-Index, and people chosing to use their favorite language instead of learning Ruby just to develop a new Web application.

So, this justifies a score of 2, why the score of 1? Honestly, I think that in a few years Ruby will enter in a COBOL-like state, where nobody is developying new Ruby applications anymore, however there is so many Ruby applications already written that the language can't die. People will stay maintaing old Ruby applications.

I may be completely wrong, though, since Ruby is a really nice language, different from COBOL. So it is not like people will avoid writting Ruby as much as possible like occurs with COBOL nowadays. I still think that Ruby will be in a dying state in 15 years.

## Python

**Score: 3**

Python is my favorite language. And is getting more popular each day. So why I think the language popularity will stagnate in 15 years?

Well, for one I think it is almost impossible to Python to reach 0-2 levels of popularity. Different from Ruby, Python have different niches: Web development (Django, Flask), Scripting (Ansible) and Scientific Computing. The language is doing really well in all those areas, however its in Scientific Computing is where (I think) most new people are comming in contact with the language.

Python popularity in Scientific Computing is mostly thanks to the libraries available for this niche, including NumPy, SciPy, Pandas and Matplotlib. However Python has well known problems, its performance in special is known to be bad. Considering that there is a new language that seems to be doing very well in performance area and is similar to Python (Julia), it isn't difficult to see Python losing this niche for another language. However, even if Python does loses its Scientific Computing niche, since the language has other niches it makes the language way more resiliant in popularity than Ruby.

The score may change for a 4 or even a (weak) 5 if Python can resolve two of its most known performance problems before another language steal its niche: GIL and (lack of) JIT. But I follow the Python community pretty close to know that those problems are really difficult to solve, unless Python break C extension compatibility (breaking compatibility with tons of popular libraries, including NumPy/SciPy). I still hope this problem can be solved, for the sake of Python future.

## PHP

**Score: 1-2**

If I wrote this post one year ago I would probably score PHP in a solid 1. However it seems that with the release of PHP 7.0 and frameworks like [Laravel](https://laravel.com/) and [Symfony](https://symfony.com/) people are rediscovering the good parts of PHP, and while the language is popularity is not necessary increasing, at least it is not decreasing as fast as before. It is still a one niche language (Web development) like Ruby, so I don't think the language will be really popular in 15 years. However, maybe sufficient people will write new code in PHP so the language will not enter in a COBOL-like state.

## C#

**Score: 4-5**

I always had the impression that C# is "Java done right". The language is cleaner, more well thought and has more features than Java. The major problem of C# was the community, since the language was close related to Windows and was pratically proprietary (even with Mono, some features and libraries were only available in Visual Studio). This made the ecosystem of C# much smaller than Java, that had an open and much more diverse ecosystem.

However, since Satya Nadella assumed as Microsoft CEO, C# started to transition to an open language. The language is itself is developed in [GitHub](https://github.com/dotnet/csharplang) and there is a fully feature and open, multi-platform compiler ([Roslyn](https://github.com/dotnet/roslyn)). I still don't know the impact that this "new Microsoft" is having in C# community, however I can only think that the impact is positive. Considering that Java is still the most language nowadays, it is not difficult to see C# beating Java in its own game, specially considering if Google abandon's Java as the primary language in [Fuchsia](https://en.wikipedia.org/wiki/Google_Fuchsia), allegedly the OS that will replace Android.

## Java

**Score: 3-4**

Oracle seems to be doing exactly the opposite of Microsoft nowadays: they seem to be trying to hurt their language popularity with controversial decisions like the [Oracle vs Google](https://arstechnica.com/series/series-oracle-v-google/) case, or [Oracle asking companies money because of "commercial features" in OpenJDK](https://www.theregister.co.uk/2016/12/16/oracle_targets_java_users_non_compliance/) (Java's most common open-source SDK). Even if you think that Oracle is right in both cases, it is nonetheless an unpopular and controversial choice that may affect Java's community.

Java most popular niche nowadays is mobile development, thanks to the insane popularity of [Android](http://www.computerworxit.com/2017/03/25/windows-slated-to-get-surpassed-by-android-as-most-used-os/). However it is not surprising that after *Oracle vs Google case*, Google is trying to migrate its mobile plataform to other Programming Language (allegedly Dart). This of course will not happen soon, Google new mobile OS will probably have some kind of Android compatibility. However it may happen faster than you can imagine. Java losing its mobile niche will probably hurt the popularity of language greatly.

Not that mobile development is Java only niche, since the language is also used for Web and System development. And there is also the amazing language ecosystem created around the Java Virtual Machine, like Clojure, Scala and Kotlin. If those languages are still popular, I can't see Java losing its relevance.

## Rust

**Score: ?**

I know that for some people this is the first language they look in this post. And I am sad to disappoint you, I don't know how well Rust will be in the future.

Rust seems to be a really nice language to (finally) substitute C and I would like to put a score of 5, however there is too much uncertainties about this language. For one, the language seems to be focused in only one niche that is Systems programming.

Except for [Servo](https://github.com/servo/servo) I don't see big open source projects developed in this language. The language first stable release is relatively recent, though, and there is ton of hype around the language in sites like Hacker News. So I think the language has the potential to get a score of 4 or 5 in 15 years. However, the hype may die and the language may get a 3 or even a 2 depending on its future.

## C

**Score: ?**

Another language that I can't put a score. The fact that C is so popular nowadays ([second most popular language in the World, only losing to Java](https://www.tiobe.com/tiobe-index/c/)) because C is the only language that really fits the Low-Level System programming niche. While other languages (like Go) can fit the necessity of a fast language for High-Level System programming, when you really need to mess up with pointers for OS and embedding programming, for example, C/C++ and Rust is your only option (well, there is also D and Nim, however they don't have the same hype), and Rust is still lacking in this departament (though it is improving). Another think that C does really well is to interface with other languages, like Python and Ruby, when you really need the most performance in your slower, high-level language.

So, if a language like Rust can take those niches from C, C score would become an 1-2. If C still remains the king, its score is a 3-4.

## C++

**Score: 3-4**

C++ is trying to be everything. And I think it is working: modern C++ (C++11, C++14, C++17) feels like a modern language, even if it still lacks basic things like modules. However, the language is in constant evolution so I think eventually the language will solve most of its problems (including long compile times).

Note that the language still kinda of a niche language that nowadays seems to be mostly focused on Gaming development, a niche that I don't think any other language will replace, not even Rust (since Rust seems to be focused more on being safe, something that games don't care). Being better in other areas may increase its popularity in the future.

## Go

**Score: 3**

Go is the language of choice when someone needs a language faster than Python/Ruby however simpler than Java/C++. This is probably why it is so popular nowadays for Web development. The language also seems to be doing well for System development, at least if you don't need the flexibility of C.

I think the language has some great characteristcs, like the fast compile times, the simplicity of the language, coroutines, etc. Its easy to see Go gaining more and more adepts from scripting languages like Python and Ruby. However, the language don't have its own particular popular niche, so I think a score of 3 is fine: it means the language will probably be the default choice for different applications, however it will not be the language that people will be excited to try.

## Javascript

**Score: 5**

This is the last language that I will analyze (at least for now). Of course, no post talking about programming languages nowadays can avoid talking about Javascript.

Javascript used to be the *ugly duck* of the programming languages, something used only to add some interactivity to a Web page, and eventually AJAX. However, since the inception of [Node.js](https://nodejs.org/), the language popularity exploded: in a few years, Javascript started to be used everywhere, from Backend development, to Mobile and even on Desktops (thanks to frameworks like [Electron](https://electron.atom.io/)). And even if the language has its quirks, after [ES6](http://es6-features.org/) the language is quite nice.

Really, it is difficult to see the language losing popularity even in 15 years from now. In Frontend development, Javascript is your only option until [WebAssembly](http://webassembly.org/) becomes a reality. And even when it does become a reality, Javascript will probably be still the first choice for Frontend. Considering that the language is evolving rapidly (the language is having constant updates in the form of ES2016 and ESnext), it is not difficult to see the language increasing its niche outside Frontend.

Well, thats it for now. Maybe I will write a part two someday about this theme someday, since I did miss tons of interesting languages (Kotlin, Julia, Perl 6, Swift, D...). However, I hope you had fun in reading my foresights in 15 years.
