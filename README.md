# Awesome WebSockets with stars

A curated list of WebSockets related principles and technologies.

[WebSocket](https://en.wikipedia.org/wiki/WebSocket) is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Contents**

* [Tools per Language](#tools-per-language)
  * [Agnostic](#agnostic)
  * [Ballerina](#ballerina)
  * [C](#c)
  * [C++](#c-1)
  * [C#](#c-2)
  * [D](#d)
  * [Elixir](#elixir)
  * [Erlang](#erlang)
  * [Go](#go)
  * [Haskell](#haskell)
  * [Java VM](#java-vm)
    * [Clojure](#clojure)
    * [Java](#java)
    * [Kotlin](#kotlin)
    * [Scala](#scala)
  * [Julia](#julia)
  * [Node.js / JavaScript](#nodejs--javascript)
  * [Perl](#perl)
  * [PHP](#php)
  * [Python](#python)
  * [R](#r)
  * [Ruby](#ruby)
  * [Rust](#rust)
  * [Swift](#swift)
  * [Protocols and APIs](#protocols-and-apis)
* [Managed / Hosted Services](#managed--hosted-services)
* [GUI Testing Tools](#gui-testing-tools)
* [Browser libraries](#browser-libraries)
* [Visualization Tools](#visualization-tools)
* [Command-Line Interface (CLI) Tools](#command-line-interface-cli-tools)
* [Real Life Stories](#real-life-stories)
* [Security](#security)
* [Theory](#theory)
  * [Articles & Papers](#articles--papers)
  * [Tutorials](#tutorials)
  * [Books](#books)
  * [Sites](#sites)
* [License](#license)
* [Contributing](#contributing)
* [Acknowledgments](#acknowledgments)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Tools per Language

### Agnostic

* [Centrifugo](https://github.com/centrifugal/centrifugo) ⭐ 10,716 | 🐛 26 | 🌐 Go | 📅 2026-09-04 - Scalable real-time messaging in language-agnostic way.
* [SocketCluster](https://github.com/SocketCluster/socketcluster) ⭐ 6,194 | 🐛 101 | 🌐 JavaScript | 📅 2026-08-21 - Scalable pub/sub WebSocket framework with support for horizontal scaling across multiple hosts and processes.
* [gwsocket](https://github.com/allinurl/gwsocket) ⭐ 817 | 🐛 12 | 🌐 C | 📅 2026-07-06 - Fast, standalone, language-agnostic WebSocket server RFC6455 compliant.
* [MinnowServer](https://github.com/RealTimeLogic/MinnowServer) ⭐ 338 | 🐛 2 | 🌐 C | 📅 2024-09-23 - A super small and fast embedded HTTP(S) WebSocket server.
* [Apache-websocket](https://github.com/disconnect/apache-websocket) ⭐ 196 | 🐛 27 | 🌐 C | 📅 2016-04-15 - Apache WebSocket module.
* [Nchan](https://nchan.slact.net) - Nchan is a scalable, flexible pub/sub server for the modern web, built as a module for the Nginx web server.
* [Websocketd](http://websocketd.com) - WebSockets the UNIX way - Full duplex messaging between web browsers and servers.

### Ballerina

* [Ballerina WebSocket Module](https://lib.ballerina.io/ballerina/websocket/latest) - Tailored WebSocket client and server implementations in Ballerina, designed and optimized for seamless integration.

### C

* [mongoose](https://github.com/cesanta/mongoose) ⭐ 13,025 | 🐛 0 | 🌐 C | 📅 2026-09-03 - Mongoose Embedded Web Server Library - Mongoose is more than an embedded webserver. It is a multi-protocol embedded networking library with functions including TCP, HTTP client and server, WebSocket client and server, MQTT client and broker and much more.
* [civetweb](https://github.com/civetweb/civetweb) ⭐ 3,447 | 🐛 243 | 🌐 C | 📅 2026-08-01 - Embedded C/C++ web server with WebSocket client and server support, easy to integrate.
* [Wslay](https://github.com/tatsuhiro-t/wslay) ⭐ 672 | 🐛 32 | 🌐 C | 📅 2022-08-25 - Designed to be embedded in other programs; freedom to choose your own network I/O. Event-based API, as well as synchronous frame-based.
* [libuwsc](https://github.com/zhaojh329/libuwsc) ⭐ 291 | 🐛 10 | 🌐 C | 📅 2022-02-21 - A Lightweight and fully asynchronous WebSocket client C library based on libubox for Embedded Linux.
* [Websocket](https://github.com/mortzdk/Websocket) ⭐ 204 | 🐛 0 | 🌐 C | 📅 2023-09-05 -  Websocket server written in C.
* [WebSockets in C](https://github.com/cjhdev/wic) ⭐ 78 | 🐛 3 | 🌐 C | 📅 2023-05-01 - A minimal implementation for embedded applications.
* [facil.io](http://facil.io) - A server/framework library for web applications, including Websockets and native pub/sub.
* [Libwebsockets](https://libwebsockets.org) - It's a lightweight pure C library built to use minimal CPU and memory resources, and provide fast throughput in both directions as client or server.

### C++

<!-- #c-1 anchor -->

* [µWebSockets](https://github.com/uNetworking/uWebSockets) ⭐ 18,980 | 🐛 48 | 🌐 C++ | 📅 2026-09-03 -  Highly scalable WebSocket server library.
* [Drogon](https://github.com/an-tao/drogon) ⭐ 14,243 | 🐛 426 | 🌐 C++ | 📅 2026-09-03 - Fast C++14/17/20 HTTP application framework with built-in WebSocket controllers.
* [POCO](https://github.com/pocoproject/poco) ⭐ 9,485 | 🐛 131 | 🌐 C++ | 📅 2026-09-04 - C++ libraries for network-centric applications, including HTTP and WebSocket classes.
* [Oat++](https://github.com/oatpp/oatpp) ⭐ 8,653 | 🐛 348 | 🌐 C++ | 📅 2025-11-12 - Light and powerful C++ web framework with async WebSocket support and zero dependencies.
* [Websocketpp](https://github.com/zaphoyd/websocketpp) ⭐ 7,718 | 🐛 483 | 🌐 C++ | 📅 2026-05-04 - C++ Websocket client/server library.
* [libhv](https://github.com/ithewei/libhv) ⭐ 7,546 | 🐛 43 | 🌐 C | 📅 2026-09-01 - A network library for developing TCP/UDP/SSL/HTTP/WebSocket client/server.
* [Crow](https://github.com/CrowCpp/Crow) ⭐ 4,961 | 🐛 87 | 🌐 C++ | 📅 2026-09-04 - Fast and easy-to-use C++ microframework for the web, with WebSocket support.
* [Beast](https://github.com/boostorg/beast) ⭐ 4,821 | 🐛 105 | 🌐 C++ | 📅 2026-09-01 - HTTP and WebSocket built on Boost.Asio in C++11.
* [Simple-WebSocket-Server](https://github.com/eidheim/Simple-WebSocket-Server) ⚠️ Archived -  A very simple, fast, multithreaded, platform independent WebSocket (WS) and WebSocket Secure (WSS) server and client library implemented using C++11, Boost.Asio and OpenSSL.
* [IXWebSocket](https://github.com/machinezone/IXWebSocket) ⭐ 791 | 🐛 70 | 🌐 C++ | 📅 2026-08-18 - Lightweight C++11 multi-threaded client library with TLS support.
* [LAppS](https://github.com/ITpC/LAppS) ⭐ 53 | 🐛 3 | 🌐 C++ | 📅 2021-01-15 - LAppS - Lua Application Server for micro-services with default communication over WebSockets.
* [QtWebSockets](http://wiki.qt.io/QtWebSockets) - The QtWebSockets module is an add-on for the Qt5 library.

### C\#

<!-- #c-2 anchor -->

* [websocket-sharp](https://github.com/sta/websocket-sharp) ⭐ 6,075 | 🐛 559 | 🌐 C# | 📅 2026-08-03 - A C# implementation of the WebSocket protocol client and server.
* [Fleck](https://github.com/statianzo/Fleck) ⭐ 2,439 | 🐛 83 | 🌐 C# | 📅 2024-07-03 - Simple C# WebSocket server implementation with no dependencies.
* [NetGain](https://github.com/StackExchange/NetGain) ⚠️ Archived - A high performance websocket server library powering Stack Overflow.
* [websocket-client](https://github.com/Marfusios/websocket-client) ⭐ 757 | 🐛 57 | 🌐 C# | 📅 2026-05-19 - Reactive, reconnecting WebSocket client for .NET based on System.Net.WebSockets.
* [websocket-manager](https://github.com/radu-matei/websocket-manager) ⭐ 455 | 🐛 34 | 🌐 C# | 📅 2020-12-31 - Real-Time library for ASP .NET Core.
* [WebSockets](https://github.com/aspnet/WebSockets) ⚠️ Archived - Implementation of the WebSocket protocol, along with client and server integration components.
* [Ninja.WebSockets](https://github.com/ninjasource/Ninja.WebSockets) ⭐ 172 | 🐛 2 | 🌐 C# | 📅 2020-11-09 - Standalone, high-performance C# WebSocket client and server implementation.
* [websocket-rpc](https://github.com/dajuric/websocket-rpc) ⚠️ Archived - WebSocket RPC library for .NET with auto JavaScript client code generation, supporting ASP.NET Core.
* [unity-websocket-server](https://github.com/shaunabanana/unity-websocket-server) ⭐ 82 | 🐛 5 | 🌐 C# | 📅 2022-06-28 - A simple, zero-dependency WebSocket server for Unity.
* [ASP.NET SignalR](http://signalr.net) - Incredibly simple real-time web for .NET.
* [WebSocketListener](http://vtortola.github.io/WebSocketListener) - Lightweight and highly scalable asynchronous WebSocket server for .NET/Mono.
* [WebSockets support in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-2.1) - This article explains how to get started with WebSockets in ASP.NET Core.

### D

* [Vibe.d](https://github.com/vibe-d/vibe.d) ⭐ 1,214 | 🐛 451 | 🌐 D | 📅 2026-07-04 - High-performance asynchronous I/O, concurrency and web application toolkit written in D.
* [Arsd:CGI](https://github.com/adamdruppe/arsd) ⭐ 563 | 🐛 53 | 🌐 D | 📅 2026-06-28 - Uniform server-side API for CGI, FastCGI, SCGI, and HTTP web applications. Offers both lower- and higher- level api options among other common (optional) things like websocket and event source serving support.
* [Serverino](https://github.com/trikko/serverino) ⭐ 79 | 🐛 1 | 🌐 D | 📅 2026-08-31 - Small and ready-to-go http server. Support for websockets included.
* [Handy](https://github.com/andrewlalis/handy-httpd) ⚠️ Archived - The simplest HTTP server for your D project.
* [Lighttp](https://github.com/Kripth/lighttp) ⭐ 24 | 🐛 6 | 🌐 D | 📅 2020-07-02 - Lightweight asynchronous HTTP and WebSocket server library for the D.
* [Websocketd](https://github.com/o3o/websocketd) ⭐ 4 | 🐛 1 | 🌐 D | 📅 2021-09-22 - A websocket server in D.

### Elixir

* [Phoenix](https://github.com/phoenixframework/phoenix) ⭐ 23,139 | 🐛 48 | 🌐 Elixir | 📅 2026-09-03 - Productive Elixir web framework with Channels for realtime, scalable WebSocket communication.
* [Phoenix LiveView](https://github.com/phoenixframework/phoenix_live_view) ⭐ 6,826 | 🐛 26 | 🌐 Elixir | 📅 2026-09-03 - Rich, realtime server-rendered UIs over WebSockets without writing JavaScript.
* [Bandit](https://github.com/mtrudel/bandit) ⭐ 1,920 | 🐛 6 | 🌐 Elixir | 📅 2026-08-31 - Pure-Elixir HTTP and WebSocket server built for Plug and WebSock.
* [WebSockex](https://github.com/Azolo/websockex) ⭐ 559 | 🐛 22 | 🌐 Elixir | 📅 2025-12-01 - Elixir WebSocket client library built on top of GenServer.

### Erlang

* [Cowboy](https://github.com/ninenines/cowboy) ⭐ 7,526 | 🐛 65 | 🌐 Erlang | 📅 2026-08-25 - Small, fast, modular HTTP server written in Erlang.
* [n2o](https://github.com/synrc/n2o) ⭐ 1,341 | 🐛 1 | 🌐 Erlang | 📅 2026-06-04 - Erlang web server on websockets.
* [Gun](https://github.com/ninenines/gun) ⭐ 949 | 🐛 24 | 🌐 Erlang | 📅 2026-07-28 - Erlang HTTP/1.1, HTTP/2 and WebSocket client library.
* [Kraken](https://github.com/Asana/kraken) ⚠️ Archived - Distributed Pubsub Server for Realtime Apps.
* [Sockjs-erlang](https://github.com/sockjs/sockjs-erlang) ⭐ 265 | 🐛 19 | 🌐 Erlang | 📅 2017-04-04 - WebSocket emulation - Erlang server.

### Go

* [Gorilla Websocket](https://github.com/gorilla/websocket) ⭐ 24,863 | 🐛 81 | 🌐 Go | 📅 2025-03-19 - WebSocket implementation for Go.
* [Ws](https://github.com/gobwas/ws) ⭐ 6,467 | 🐛 28 | 🌐 Go | 📅 2026-02-12 - Tiny WebSocket library for Go.
* [1m-go-websockets](https://github.com/eranyanay/1m-go-websockets) ⭐ 5,994 | 🐛 3 | 🌐 Go | 📅 2022-08-14 - Handling 1M websockets connections in Go.
* [go-socket.io](https://github.com/googollee/go-socket.io) ⚠️ Archived - Socket.IO library for Go, a realtime application framework.
* [coder/websocket](https://github.com/coder/websocket) ⭐ 5,451 | 🐛 71 | 🌐 Go | 📅 2026-06-15 - A minimal and idiomatic WebSocket library for Go (formerly nhooyr/websocket).
* [Melody](https://github.com/olahol/melody) ⭐ 4,083 | 🐛 14 | 🌐 Go | 📅 2025-10-28 - Minimalist framework for dealing with WebSocket sessions, including broadcasting and message buffering.
* [nbio](https://github.com/lesismal/nbio) ⭐ 2,755 | 🐛 0 | 🌐 Go | 📅 2026-08-09 - Non-blocking, event-driven networking framework with high-performance WebSocket support and low memory usage.
* [GWS](https://github.com/lxzan/gws) ⭐ 1,797 | 🐛 0 | 🌐 Go | 📅 2026-07-27 - Simple, fast, reliable websocket server & client, supports running over tcp/kcp/unix domain socket.
* [Centrifuge](https://github.com/centrifugal/centrifuge) ⭐ 1,466 | 🐛 13 | 🌐 Go | 📅 2026-09-04 - Real-time messaging library for Go with scalability in mind.
* [Fiber WebSocket](https://github.com/gofiber/websocket) ⚠️ Archived - WebSocket middleware for the Fiber web framework, built on Fasthttp.
* [KubeStellar Console](https://github.com/kubestellar/console) ⭐ 132 | 🐛 89 | 🌐 TypeScript | 📅 2026-09-04 - AI-powered multi-cluster Kubernetes dashboard using WebSockets for real-time cluster communication and live observability streams.
* [greatws](https://github.com/antlabs/greatws) ⭐ 86 | 🐛 4 | 🌐 Go | 📅 2025-07-06 - Event-driven WebSocket server able to handle millions of connections with low memory.
* [Velaros](https://github.com/RobertWHurst/Velaros) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2026-07-24 - A lightweight framework with HTTP-style routing, bidirectional messaging, and middleware.
* [gotify/server](https://gotify.net/) - A simple server for sending and receiving messages in real-time per web socket.
* [Websocket](https://godoc.org/golang.org/x/net/websocket) - Package Websocket implements a client and server for the WebSocket protocol as specified in RFC 6455.

### Haskell

* [Websockets](https://github.com/jaspervdj/websockets) ⭐ 416 | 🐛 38 | 🌐 Haskell | 📅 2026-04-20 - A Haskell library for creating WebSocket-capable servers.
* [n2o](https://github.com/o3/n2o) ⭐ 47 | 🐛 5 | 🌐 Haskell | 📅 2022-02-16 - Haskell implementation of Erlang's n2o - web server on websockets.

### Java VM

#### Clojure

* [http-kit](https://github.com/http-kit/http-kit) ⭐ 2,565 | 🐛 52 | 🌐 Java | 📅 2026-08-21 - Minimalist, high-performance HTTP server and client with async WebSocket support.
* [Sente](https://github.com/ptaoussanis/sente) ⭐ 1,791 | 🐛 4 | 🌐 Clojure | 📅 2026-08-21 - Realtime web comms for Clojure/Script.
* [Chord](https://github.com/jarohen/chord) ⭐ 442 | 🐛 7 | 🌐 Clojure | 📅 2020-07-12 - Library designed to bridge the gap between the triad of CLJ/CLJS, web-sockets and core.async.
* [Luminusweb](http://www.luminusweb.net/docs/websockets.md) - Luminus is a Clojure micro-framework based on a set of lightweight libraries.

#### Java

* [Netty](https://github.com/netty/netty) ⭐ 35,046 | 🐛 662 | 🌐 Java | 📅 2026-09-04 - Asynchronous event-driven network framework with full WebSocket codec support.
* [Vert.x](https://github.com/eclipse-vertx/vert.x) ⭐ 14,684 | 🐛 225 | 🌐 Java | 📅 2026-09-04 - Reactive, polyglot toolkit for the JVM with first-class WebSocket client and server APIs.
* [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket) ⭐ 10,806 | 🐛 58 | 🌐 Java | 📅 2026-01-13 - Barebones WebSocket client and server implementation written in 100% Java.
* [Javalin](https://github.com/javalin/javalin) ⭐ 8,342 | 🐛 18 | 🌐 Kotlin | 📅 2026-09-04 - Lightweight web framework for Java and Kotlin with simple WebSocket handlers.
* [Jetty](https://github.com/jetty/jetty.project) ⭐ 4,092 | 🐛 274 | 🌐 Java | 📅 2026-09-04 - Lightweight, embeddable Java web server and servlet container with Jakarta and native WebSocket support.
* [Atmosphere](https://github.com/Atmosphere/atmosphere) ⭐ 3,808 | 🐛 7 | 🌐 Java | 📅 2026-09-04 - Realtime Client Server Framework for the JVM, supporting WebSockets with Cross-Browser Fallbacks.
* [Undertow](https://github.com/undertow-io/undertow) ⭐ 3,759 | 🐛 47 | 🌐 Java | 📅 2026-09-03 - High-performance web server (WildFly's core) with a dedicated WebSocket API.
* [nv-websocket-client](https://github.com/TakahikoKawasaki/nv-websocket-client) ⭐ 2,052 | 🐛 93 | 🌐 Java | 📅 2024-01-28 - High-quality WebSocket client implementation in Java which.
* [Webbit](https://github.com/webbit/webbit) ⭐ 819 | 🐛 47 | 🌐 Java | 📅 2023-12-17 - Java event based WebSocket and HTTP server.
* [Project Tyrus](https://github.com/eclipse-ee4j/tyrus) ⭐ 128 | 🐛 107 | 🌐 Java | 📅 2026-03-15 - JSR 356: Java API for WebSocket - Reference Implementation.
* [Spring WebSocket](https://docs.spring.io/spring-framework/reference/web/websocket.html) - WebSocket and STOMP messaging support built into the Spring Framework.

#### Kotlin

* [OkHttp](https://github.com/square/okhttp) ⭐ 47,060 | 🐛 144 | 🌐 Kotlin | 📅 2026-09-04 - HTTP client for the JVM and Android with a robust WebSocket client.
* [Ktor](https://github.com/ktorio/ktor) ⭐ 14,514 | 🐛 184 | 🌐 Kotlin | 📅 2026-09-04 - JetBrains' Kotlin async framework with built-in WebSocket client and server support.
* [Scarlet](https://github.com/Tinder/Scarlet) ⭐ 3,255 | 🐛 108 | 🌐 Kotlin | 📅 2025-11-21 - Tinder's Retrofit inspired WebSocket client for Kotlin, Java, and Android.

#### Scala

* [http4s](https://github.com/http4s/http4s) ⭐ 2,626 | 🐛 382 | 🌐 Scala | 📅 2026-09-04 - Typeful, functional, streaming HTTP for Scala with WebSocket support.
* [ZIO HTTP](https://github.com/zio/zio-http) ⭐ 872 | 🐛 60 | 🌐 Scala | 📅 2026-09-03 - High-performance, functional Scala HTTP library with WebSocket support built on ZIO.
* [Apache Pekko HTTP](https://github.com/apache/pekko-http) ⭐ 196 | 🐛 79 | 🌐 Scala | 📅 2026-09-02 - Streaming WebSocket client and server directives; the Apache-licensed Akka HTTP fork.
* [Finagle-websocket](https://github.com/finagle/finagle-websocket) ⭐ 37 | 🐛 7 | 🌐 Scala | 📅 2017-12-21 - Finagle Websocket clients and servers.
* [Play](https://www.playframework.com/documentation/2.5.x/ScalaWebSockets) - The high velocity web framework for Java and Scala.

### Julia

* [HTTP.jl](https://github.com/JuliaWeb/HTTP.jl) ⭐ 688 | 🐛 6 | 🌐 Julia | 📅 2026-08-31 - HTTP library for Julia with support on Websockets.
* [WebSockets.jl](https://github.com/JuliaWeb/WebSockets.jl) ⭐ 161 | 🐛 9 | 🌐 Julia | 📅 2022-11-29 - A WebSockets library for Julia.

### Node.js / JavaScript

* [Ws](https://github.com/websockets/ws) ⭐ 22,799 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-13 - `ws`: The fastest cross platform RFC-6455 WebSocket implementation for Node.js.
* [uws](https://github.com/uNetworking/uWebSockets.js) ⭐ 9,152 | 🐛 22 | 🌐 C++ | 📅 2026-07-11 - Tiny WebSockets (access to the C++ library, µWebSockets, via Node.js)
* [PartySocket](https://github.com/partykit/partykit/tree/main/packages/partysocket) ⭐ 5,700 | 🐛 92 | 🌐 TypeScript | 📅 2026-01-29 - Robust WebSocket client with automatic reconnection and buffering, usable against any WS server.
* [soketi](https://github.com/soketi/soketi) ⭐ 5,634 | 🐛 142 | 🌐 TypeScript | 📅 2025-03-03 - Just another simple, fast, and resilient open-source WebSockets server. Built on top of uWebSockets.js.
* [WebSocket-Node](https://github.com/theturtle32/WebSocket-Node) ⭐ 3,781 | 🐛 74 | 🌐 JavaScript | 📅 2025-10-06 - WebSocket Implementation for Node.JS (Draft -08 through the final RFC 6455).
* [Sockette](https://github.com/lukeed/sockette) ⭐ 2,468 | 🐛 10 | 🌐 JavaScript | 📅 2024-01-20 - WebSocket client that will automatically reconnect if the connection is lost.
* [Sockjs-node](https://github.com/sockjs/sockjs-node) ⭐ 2,101 | 🐛 19 | 🌐 JavaScript | 📅 2026-07-21 - WebSocket emulation - Node.js server.
* [graphql-ws](https://github.com/enisdenjo/graphql-ws) ⭐ 1,871 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-06 - Coherent, zero-dependency, spec-compliant GraphQL over WebSocket server and client.
* [Nodejs-websocket](https://github.com/sitegui/nodejs-websocket) ⭐ 736 | 🐛 15 | 📅 2025-12-02 - Node.js module for websocket server and client.
* [y-websocket](https://github.com/yjs/y-websocket) ⭐ 710 | 🐛 38 | 🌐 JavaScript | 📅 2026-08-06 - WebSocket connection provider for Yjs, enabling real-time collaborative editing and CRDT sync.
* [rpc-websockets](https://github.com/elpheria/rpc-websockets) ⭐ 626 | 🐛 17 | 🌐 JavaScript | 📅 2026-05-15 - JSON-RPC 2.0 implementation over WebSockets for Node.js and JavaScript/TypeScript.
* [faye-websocket-node](https://github.com/faye/faye-websocket-node) ⭐ 612 | 🐛 5 | 🌐 JavaScript | 📅 2023-09-07 - Standards-compliant WebSocket client and server.
* [websocket-as-promised](https://github.com/vitalets/websocket-as-promised) ⭐ 601 | 🐛 6 | 🌐 JavaScript | 📅 2025-04-22 - Promise-based W3C WebSocket wrapper: allows to use promises when connecting, disconnecting and messaging with WebSocket server.
* [ws-wrapper](https://github.com/bminer/ws-wrapper) ⭐ 86 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-04 - Lightweight WebSocket wrapper that provides a socket.io-like event-handler API along with Promise-based requests.
* [ws-server-wrapper](https://github.com/bminer/ws-server-wrapper) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-30 - Companion library for ws-wrapper for the server-side.
* [Bun WebSockets](https://bun.sh/docs/api/websockets) - Native high-performance WebSocket server built into the Bun runtime with pub/sub support.
* [deepstream.io](https://deepstream.io/) - Open realtime server a fast, secure and scalable realtime server for mobile, web & iot.
* [Hono WebSocket Helper](https://hono.dev/docs/helpers/websocket) - Built-in WebSocket helper for the Hono framework across Cloudflare Workers, Bun, Deno, and Node.js.
* [netflux](https://coast-team.github.io/netflux/) - JavaScript client and server side transport API based on WebRTC & WebSocket
* [Socket.IO](http://socket.io/) - Featuring the fastest and most reliable real-time engine.
* [tRPC Subscriptions](https://trpc.io/docs/server/subscriptions) - End-to-end typesafe real-time subscriptions over WebSockets for TypeScript apps.
* [wspromisify](https://www.npmjs.com/package/wspromisify) - Makes WebSockets async/await ready with a lot of yummies.
* [ZilaWS Server](https://zilaws.com) - A very easy-to-use and fast WS implementation with async/await eventhandlers and extendable classes.

### Perl

* [`AnyEvent::WebSocket::Server`](https://metacpan.org/pod/AnyEvent::WebSocket::Server) - WebSocket server for AnyEvent
* [`Dancer2::Plugin::WebSocket`](https://metacpan.org/pod/Dancer2::Plugin::WebSocket) - add a websocket interface to your Dancer2 app
* [`Mojolicious`](https://metacpan.org/pod/distribution/Mojolicious/lib/Mojolicious/Guides/Routing.pod#WebSockets) - An amazing real-time web framework built on top of the powerful Mojo web development toolkit and comes with websockets built in.
* [`Net::WebSocket`](https://metacpan.org/pod/Net::WebSocket::Server) - Super-flexible, minimal client & server library
* [`Net::WebSocket::Server`](https://metacpan.org/pod/Net::WebSocket::Server) - Straightforward Perl WebSocket server with minimal dependencies.
* [`Plack::App::WebSocket`](https://metacpan.org/pod/Plack::App::WebSocket) - WebSocket server as a plack/PSGI application

### PHP

* [Laravel Websockets](https://github.com/beyondcode/laravel-websockets) ⚠️ Archived - A package for Laravel 5.7 and up that will get your application started with WebSockets in no-time!
* [Php-websocket](https://github.com/nekudo/php-websocket) ⭐ 588 | 🐛 5 | 🌐 PHP | 📅 2022-10-22 - Simple PHP WebSocket implementation for PHP 5.3.
* [Phpws](https://github.com/Devristo/phpws) ⚠️ Archived - PHP Web Socket server.
* [Ratchet](http://socketo.me/) - Ratchet is a loosely coupled PHP library providing developers with tools to create real time, bi-directional applications between clients and servers over WebSockets.
* [Sandstone](https://eole-io.github.io/sandstone/) - Microframework to build a real time Rest API.

### Python

* [FastAPI](https://github.com/fastapi/fastapi) ⭐ 102,077 | 🐛 81 | 🌐 Python | 📅 2026-09-01 - Modern, high-performance web framework for building APIs, with first-class WebSocket support.
* [aiohttp](https://github.com/aio-libs/aiohttp) ⭐ 16,532 | 🐛 219 | 🌐 Python | 📅 2026-09-04 - Asynchronous HTTP client/server framework for asyncio, with built-in WebSocket client and server support.
* [Websockets](https://websockets.readthedocs.io) ([code](https://github.com/aaugustin/websockets) ⭐ 5,715 | 🐛 2 | 🌐 Python | 📅 2026-08-29) - Websockets is a library for developing WebSocket servers and clients in Python 3.
* [python-socketio](https://github.com/miguelgrinberg/python-socketio) ⭐ 4,368 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - Python implementation of the Socket.IO realtime client and server.
* [websocket-client](https://github.com/websocket-client/websocket-client) ⭐ 3,706 | 🐛 33 | 🌐 Python | 📅 2026-08-31 - Popular, long-standing synchronous client for Python.
* [Autobahn.ws](https://github.com/crossbario/autobahn-python) ⭐ 2,543 | 🐛 187 | 🌐 Python | 📅 2026-07-15 - Open-source real-time framework for Web, Mobile & Internet of Things.
* [Socketify.py](https://github.com/cirospaciari/socketify.py) ⭐ 1,714 | 🐛 51 | 🌐 Python | 📅 2026-08-17 - Fast WebSocket and HTTP server for Python built on uWebSockets, with ASGI/WSGI support.
* [python-websocket-server](https://github.com/Pithikos/python-websocket-server) ⭐ 1,178 | 🐛 40 | 🌐 Python | 📅 2025-10-07 - Minimal, dependency-free WebSocket server written in pure Python.
* [simple-websocket](https://github.com/miguelgrinberg/simple-websocket) ⭐ 88 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - Simple WebSocket server and client for Python built on WSGI/ASGI.
* [WebRockets](https://github.com/ploMP4/webrockets) ⭐ 76 | 🐛 1 | 🌐 Rust | 📅 2026-07-23 - Rust-powered WebSocket server with Django integration, message pattern matching, Pydantic validation, and more.
* [Simple Http Server](https://github.com/keijack/python-simple-http-server) ⚠️ Archived A simple HTTP server, including support of numerous websocket events like `on_text_message`, `on_binary_message` etc. And even `on_binary_frame`.
* [WebSocket Benchmarker](https://github.com/healeycodes/websocket-benchmarker) ⭐ 29 | 🐛 2 | 🌐 Python | 📅 2019-03-27 - CLI tool for benchmarking WebSocket Servers.
* [Django Channels](https://channels.readthedocs.io/en/latest) - Extends [Django](https://www.djangoproject.com/) with  WebSocket, long-poll HTTP, task offloading and other async support.
* [Picows](https://picows.readthedocs.io/en/stable/) - Ultra-fast WebSocket client and server library for asyncio.
* [Starlette](https://www.starlette.io/websockets/)
* [Tornado](http://www.tornadoweb.org/) - Tornado is a Python web framework and asynchronous networking library, originally developed at FriendFeed.
* [Ws4py](https://ws4py.readthedocs.io/en/latest) - WebSocket package for Python.

### R

* [httpuv](https://cran.r-project.org/package=httpuv) - Provides low-level socket and protocol support for WebSocket (and HTTP) servers in R. Built on top of the [libuv](https://github.com/libuv/libuv) ⭐ 27,157 | 🐛 232 | 🌐 C | 📅 2026-09-01 and [http-parser](https://github.com/nodejs/http-parser) ⚠️ Archived C libraries.
* [routr](https://cran.r-project.org/package=routr) - A simple router for WebSocket (and HTTP) requests in R.
* [websocket](https://cran.r-project.org/package=websocket) - Provides a WebSocket client interface for R.

### Ruby

* [websocket-rails](https://github.com/websocket-rails/websocket-rails) ⭐ 1,714 | 🐛 200 | 🌐 Ruby | 📅 2024-02-14 - Plug and play websocket support for ruby on rails.
* [Em-websocket](https://github.com/igrigorik/em-websocket) ⭐ 1,688 | 🐛 26 | 🌐 Ruby | 📅 2021-11-11 - EventMachine based WebSocket server.
* [Slanger](https://github.com/stevegraham/slanger) ⚠️ Archived - Open Pusher implementation compatible with Pusher libraries.
* [Rage](https://github.com/rage-rb/rage) ⭐ 1,409 | 🐛 18 | 🌐 Ruby | 📅 2026-09-01 - Fast WebSocket server compatible with Action Cable.
* [render\_sync](https://github.com/chrismccord/render_sync) ⭐ 1,384 | 🐛 39 | 🌐 Ruby | 📅 2019-05-25 - Real-time Rails Partials.
* [Faye-websocket-ruby](https://github.com/faye/faye-websocket-ruby) ⭐ 1,059 | 🐛 6 | 🌐 Ruby | 📅 2025-05-25 - Standards-compliant WebSocket client and server.
* [Iodine](https://github.com/boazsegev/iodine) ⭐ 971 | 🐛 22 | 🌐 C | 📅 2026-08-20 - WebSocket/HTTP server with integrated pub/sub and optional Redis support.
* [Websocket-ruby](https://github.com/imanel/websocket-ruby) ⭐ 464 | 🐛 3 | 🌐 Ruby | 📅 2026-07-25 - Universal Ruby library to handle WebSocket protocol.
* [Scorched](https://github.com/wardrop/Scorched) ⭐ 274 | 🐛 0 | 🌐 Ruby | 📅 2026-07-31 - Light-weight web framework for Ruby.
* [Websocket-driver-ruby](https://github.com/faye/websocket-driver-ruby) ⭐ 238 | 🐛 11 | 🌐 Ruby | 📅 2026-06-23 - WebSocket protocol handler with pluggable I/O.
* [AnyCable](http://anycable.io/) - Polyglot replacement for Ruby WebSocket servers with Action Cable protocol.
* [Firehose](http://firehose.io/) - Build realtime Ruby web applications. Created by the fine folks at Poll Everywhere.

### Rust

* [Axum](https://github.com/tokio-rs/axum) ⭐ 27,014 | 🐛 78 | 🌐 Rust | 📅 2026-09-01 - Ergonomic and modular web framework built with Tokio, Tower, and Hyper, with built-in WebSocket support.
* [warp](https://github.com/seanmonstar/warp) ⭐ 10,366 | 🐛 232 | 🌐 Rust | 📅 2026-07-28 - Composable, Tokio-based web server framework with a WebSocket filter.
* [ntex](https://github.com/ntex-rs/ntex) ⭐ 2,533 | 🐛 5 | 🌐 Rust | 📅 2026-09-04 - Powerful, pragmatic and fast web framework with WebSocket support.
* [Tokio-Tungstenite](https://github.com/snapview/tokio-tungstenite) ⭐ 2,501 | 🐛 18 | 🌐 Rust | 📅 2026-07-11 - Tokio binding for Tungstenite, the Lightweight stream-based WebSocket implementation
* [Tungstenite](https://github.com/snapview/tungstenite-rs) ⭐ 2,387 | 🐛 47 | 🌐 Rust | 📅 2026-07-11 - Lightweight stream-based WebSocket implementation
* [rust-websocket](https://github.com/websockets-rs/rust-websocket) ⭐ 1,615 | 🐛 45 | 🌐 Rust | 📅 2026-08-17 - RFC6455 library providing both synchronous and asynchronous client and server.
* [Fastwebsockets](https://github.com/denoland/fastwebsockets) ⭐ 1,134 | 🐛 19 | 🌐 Rust | 📅 2026-07-31 - A fast RFC6455 WebSocket server implementation
* [async-tungstenite](https://github.com/sdroege/async-tungstenite) ⭐ 443 | 🐛 7 | 🌐 Rust | 📅 2026-07-28 - Async binding for Tungstenite, runtime-agnostic across async-std, tokio, and smol.
* [wtx](https://github.com/c410-f3r/wtx) ⭐ 400 | 🐛 6 | 🌐 Rust | 📅 2026-08-30 - Client and server with encryption support.
* [tide-websockets](https://github.com/http-rs/tide-websockets) ⭐ 74 | 🐛 6 | 🌐 Rust | 📅 2023-05-21 - WebSocket handler for the Tide web framework.
* [Ratchet](https://github.com/swimos/ratchet) ⭐ 60 | 🐛 10 | 🌐 Rust | 📅 2026-06-04 - Ratchet is a fast, lightweight and fully asynchronous implementation of the WebSocket protocol with support for extensions and Deflate.
* [Websocket Core](https://github.com/bitwyre/websocket_core) ⭐ 13 | 🐛 1 | 🌐 Rust | 📅 2019-11-20 - Rust Websocket server for periodic message broadcast
* [Actix](https://actix.rs/docs/websockets) - A Rust web framework with support for the Websocket Protocol

### Swift

* [Starscream](https://github.com/daltoniam/Starscream) ⭐ 8,646 | 🐛 172 | 🌐 Swift | 📅 2024-05-16 - Conforming WebSocket (RFC 6455) client library in Swift for iOS and macOS.
* [SwiftNIO](https://github.com/apple/swift-nio) ⭐ 8,511 | 🐛 296 | 🌐 Swift | 📅 2026-09-04 - Apple's cross-platform async event-driven network framework, a foundation for WebSocket servers.
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) ⭐ 5,294 | 🐛 259 | 🌐 Swift | 📅 2024-10-01 - Official Socket.IO client for Swift.
* [Hummingbird](https://github.com/hummingbird-project/hummingbird) ⭐ 1,881 | 🐛 25 | 🌐 Swift | 📅 2026-09-04 - Lightweight, flexible Swift server framework on SwiftNIO with WebSocket support.
* [WebsocketKit](https://github.com/vapor/websocket-kit) ⭐ 313 | 🐛 20 | 🌐 Swift | 📅 2026-07-17 - A low level WebSocket client library built on SwiftNIO.
* [Vapor](https://vapor.codes) - A high level web framework for Swift.

### Protocols and APIs

* [TikTok-Live-Connector](https://github.com/zerodytrash/TikTok-Live-Connector/) ⭐ 2,139 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-18 - Open source TikTok LIVE stream events API, with delivery over WebSocket. The predominant & native TypeScript library for TikTok LIVE integrations.
* [TikTokLive](https://github.com/isaackogan/TikTokLive/) ⭐ 1,546 | 🐛 0 | 🌐 Python | 📅 2026-08-18 - A TikTok LIVE API Client built in Python, with strict mypy type safety & a copyleft license. Real-time TikTok LIVE stream events (gifts, chats, etc.) over WebSocket.
* [TikTokLiveJava](https://github.com/jwdeveloper/TikTokLiveJava) ⭐ 211 | 🐛 1 | 🌐 Java | 📅 2026-08-13 - A TikTok LIVE API Client built in Java. Real-time TikTok LIVE stream events (gifts, chats, etc.) over WebSockets.
* [RFC6455](https://www.rfc-editor.org/rfc/rfc6455) - The WebSocket Protocol.
* [RFC7692](https://www.rfc-editor.org/rfc/rfc7692) - Compression Extensions for WebSocket (permessage-deflate).
* [RFC8441](https://www.rfc-editor.org/rfc/rfc8441) - Bootstrapping WebSockets with HTTP/2.
* [The WebSocket API](https://websockets.spec.whatwg.org) - WebSockets - Living Standard.
* [Live Tennis API](https://docs.livetennisapi.com) - Real-time tennis score events (point-by-point state, serving, break points) streamed over WebSocket on paid tiers, with a free REST tier. SDKs for [Node.js](https://www.npmjs.com/package/livetennisapi) and [Python](https://pypi.org/project/livetennisapi/).
* [TikTool Live](https://tik.tools/docs) - Real-time TikTok LIVE stream events (chat, gifts, viewers) via WebSocket. SDKs for [Node.js](https://www.npmjs.com/package/tiktok-live-api) and [Python](https://pypi.org/project/tiktok-live-api/).
* [WAMP](https://wamp-proto.org) - The Web Application Messaging Protocol: routed RPC and publish/subscribe over WebSocket.

## Managed / Hosted Services

* [Ably](https://ably.com) - Managed pub/sub realtime platform with WebSocket-based messaging, presence, and guaranteed delivery.
* [AWS API Gateway WebSocket APIs](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html) - Managed WebSocket APIs that route messages to Lambda and other AWS backends.
* [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) - Stateful serverless coordination primitive commonly used to build WebSocket rooms and realtime backends at the edge.
* [Cloudflare Workers WebSockets](https://developers.cloudflare.com/workers/runtime-apis/websockets/) - Native WebSocket support in Cloudflare Workers, including hibernatable connections.
* [Liveblocks](https://www.liveblocks.io) - Hosted realtime collaboration infrastructure providing presence, storage, and comments over WebSockets.
* [Momento Topics](https://www.gomomento.com) - Serverless pub/sub and caching service with realtime topics accessible over WebSockets.
* [PartyKit](https://github.com/partykit/partykit) ⭐ 5,700 | 🐛 92 | 🌐 TypeScript | 📅 2026-01-29 - Open-source platform for building realtime multiplayer apps on Cloudflare with a batteries-included WebSocket server abstraction.
* [PubNub](https://www.pubnub.com) - Realtime edge messaging platform delivering pub/sub over WebSockets at global scale.
* [Pusher Channels](https://pusher.com) - Hosted WebSocket API for pub/sub realtime features with client SDKs across platforms.
* [Supabase Realtime](https://supabase.com/docs/guides/realtime) - Realtime engine broadcasting Postgres changes, presence, and messages to clients over WebSockets.

## GUI Testing Tools

* [Apidog](https://apidog.com/websocket-testing/) - All-in-one API platform with a dedicated WebSocket debugging client for messages, params and auth.
* [Bruno](https://www.usebruno.com) - Open-source, offline-first API client with WebSocket support and git-friendly plain-text collections.
* [Firecamp](https://firecamp.io/websocket) - Full-featured GUI WebSocket testing client which helps Dev team to test WebSocket events visually. Test APIs, save them in the project and share it with your team.
* [Hoppscotch Realtime](https://hoppscotch.io/realtime) - Free, open-source browser client for testing WebSocket, SSE, Socket.IO and MQTT connections.
* [Insomnia](https://insomnia.rest) - Open-source API client with native WebSocket request support alongside REST, GraphQL and gRPC.
* [Postman WebSocket](https://learning.postman.com/docs/sending-requests/websocket/create-a-websocket-request/) - Send and inspect raw WebSocket and Socket.IO requests inside Postman, with saved history and collections.
* [Simple WebSocket Client](https://chrome.google.com/webstore/detail/simple-websocket-client/pfdhoblngboilpfeibdedpjgfnlcodoo) - Simple WebSocket Client (Chrome Extension).
* [Thunder Client](https://www.thunderclient.com) - Lightweight VS Code REST and WebSocket client for testing connections without leaving the editor.
* [WebSocket.in](https://www.websocket.in) - Browser-based WebSocket tester plus free public echo and broadcast endpoints for quick checks.
* [WebSocket King](https://websocketking.com) - A browser based WebSocket testing client that supports multiple simultanious connections, logs of incoming and outgoing messages, custom protocols and multiple projects.

## Browser libraries

* [react-use-websocket](https://github.com/robtaussig/react-use-websocket) ⭐ 1,886 | 🐛 95 | 🌐 TypeScript | 📅 2025-02-04 - React hook for WebSocket connections with reconnection, message queueing, and shared connections.
* [WSGO](https://github.com/melishev/wsgo) ⚠️ Archived - like Axios.js, only for WebSocket, adds handy debugging tools
* [ZilaWS Client](https://zilaws.com) - A very easy-to-use and fast WS implementation with async/await eventhandlers.

## Visualization Tools

* [Foxglove ws-protocol](https://github.com/foxglove/ws-protocol) ⚠️ Archived - Websocket protocol for visualization of multimodal data.

## Command-Line Interface (CLI) Tools

* [websocketd](https://github.com/joewalnes/websocketd) ⭐ 17,463 | 🐛 3 | 🌐 Go | 📅 2026-09-02 - Turn any program that uses STDIN/STDOUT into a WebSocket server. Like inetd, but for WebSockets.
* [websocat](https://github.com/vi/websocat) ⭐ 8,683 | 🐛 158 | 🌐 Rust | 📅 2026-08-13 - Command-line client for WebSockets, like netcat (or curl) for ws\:// with advanced socat-like functions.
* [wscat](https://github.com/websockets/wscat) ⭐ 2,774 | 🐛 36 | 🌐 JavaScript | 📅 2025-05-03 - WebSocket cat.
* [wsta](https://github.com/esphen/wsta) ⭐ 632 | 🐛 12 | 🌐 Rust | 📅 2018-11-06 - A CLI development tool for WebSocket APIs.
* [ws](https://github.com/hashrocket/ws) ⭐ 434 | 🐛 17 | 🌐 Go | 📅 2023-03-08 - websocket command line tool.
* [claws](https://github.com/thehowl/claws) ⭐ 315 | 🐛 7 | 🌐 Go | 📅 2026-01-24 - Awesome WebSocket Client - an interactive command line client for testing websocket servers.
* [wssh](https://github.com/progrium/wssh) ⭐ 267 | 🐛 24 | 🌐 Python | 📅 2023-09-25 - wssh ("wish") is a command-line utility/shell for WebSocket inspired by netcat.
* [iola](https://github.com/pvarentsov/iola) ⭐ 170 | 🐛 0 | 🌐 TypeScript | 📅 2023-10-12 - Socket client with Rest API (WebSocket, Socket.IO, TCP, Unix socket).
* [wsc](https://github.com/raphael/wsc) ⭐ 50 | 🐛 3 | 🌐 Go | 📅 2017-10-26 - A tiny command line websocket client written in Go.
* [ws-tool](https://github.com/plantain-00/ws-tool) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2021-09-25 - A Develop Tool to Test WebSocket, Socket.IO, Stomp, Bayeux, HTTP, TCP, UDP, WebRTC, DNS API.
* [ws-cli](https://github.com/kseo/ws-cli) ⭐ 17 | 🐛 1 | 🌐 Go | 📅 2016-10-14 - WebSocket Command Line Client written in Go.

## Real Life Stories

* [The top 10 realtime web apps](http://www.creativebloq.com/app-design/top-10-realtime-web-apps-5133752)
* [Super sync sports](https://blog.chromium.org/2013/02/on-track-with-chrome-super-sync-sports.html)
* [Kaazing](https://kaazing.com/)
* [Taskade](https://taskade.com) - Real-time collaborative task lists and outlines.

## Security

* [WebSockets - An Introduction](https://gist.github.com/subudeepak/9897212) - The problems and some security implications of websockets - Cross-site WebSockets Scripting (XSWS).
* [Hacking with WebSockets](https://media.blackhat.com/bh-us-12/Briefings/Shekyan/BH_US_12_Shekyan_Toukharian_Hacking_Websocket_Slides.pdf) - Talk on Blackhat USA 2012 Conference.
* [Testing for WebSockets Security Vulnerabilities](https://portswigger.net/web-security/websockets) - Interactive vulnerable WebSocket demos that provide hands-on learning of WebSocket security risks
* [Testing WebSockets](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/11-Client-side_Testing/10-Testing_WebSockets) - OWASP Web Security Testing Guide (WSTG), client-side WebSocket testing chapter.
* [Websockets Auth](http://stratumsecurity.ghost.io/2016/06/13/websockets-auth) - Journey into WebSockets Authentication/Authorization.
* [WebSocket Security](https://devcenter.heroku.com/articles/websocket-security) - The WebSocket protocol is a young technology, and brings with it some risks. Decades of experience have taught the web community some best practices around HTTP security, but the security best practices in the WebSocket world aren’t firmly established, and continue to evolve. Nevertheless, some themes have emerged and they are described in this article.
* [Cross-Site WebSocket Hijacking](http://www.christian-schneider.net/CrossSiteWebSocketHijacking.html) - Cross-Site WebSocket Hijacking (CSWSH) - Web Application Security Blog.
* [Cross-site WebSocket hijacking labs](https://portswigger.net/web-security/websockets/cross-site-websocket-hijacking) - PortSwigger deep-dive on CSWSH with interactive labs.

## Theory

### Articles & Papers

* [An introduction to Websockets](http://blog.teamtreehouse.com/an-introduction-to-websockets) - Brief History of Real-Time Web Applications.
* [Introducing WebSockets: Bringing Sockets to the Web](https://www.html5rocks.com/en/tutorials/websockets/basics/) - The Problem: Low Latency Client-Server and Server-Client Connections.
* [About HTML5 WebSocket](https://websocket.org/aboutwebsocket.html) - About HTML5 WebSocket.
* [Node.js WebSocket](https://medium.com/@denizozger/finding-the-right-node-js-websocket-implementation-b63bfca0539#.q2313as8p) - Finding the right Node.js WebSocket implementation.
* [Websockets 101](http://lucumr.pocoo.org/2012/9/24/websockets-101/) - Armin Ronacher's Thoughts and Writings (creator of Flask).
* [Real-time Apps](https://www.sitepoint.com/real-time-apps-websockets-server-sent-events/) - Building Real-time Apps with Websockets & Server-Sent Events.
* [Real-Time Web by Paul Banks](https://banksco.de/p/state-of-realtime-web-2016.html) - The State of Real-Time Web in 2016.
* [Are WebSockets the future?](https://samsaffron.com/archive/2015/12/29/websockets-caution-required) - WebSockets, caution required!
* [MSDN Microsoft Blog](https://msdn.microsoft.com/en-us/hh563510.aspx) - The Dangers of HTML5: WebSockets and Stable Standards.
* [Webpush Internet-Draft](https://martinthomson.github.io/drafts/draft-thomson-webpush-http2.html) - Generic Event Delivery Using HTTP Push.
* [Full Stack Python](https://www.fullstackpython.com/websockets.html) - WebSockets on Python.
* [Do you really need WebSockets?](https://blog.stanko.io/do-you-really-need-websockets-343aed40aa9b) - WebSockets explanation.

### Tutorials

* [Honeybadger.IO](http://blog.honeybadger.io/building-a-simple-websockets-server-from-scratch-in-ruby) - Building a simple websockets server from scratch in Ruby.
* [David Walsh](https://davidwalsh.name/websocket) - WebSocket and Socket.IO.
* [Implementing a WebSocket server with Node.js](https://medium.com/hackernoon/implementing-a-websocket-server-with-node-js-d9b78ec5ffa8).
* [Lostmoa](https://lostmoa.com/tags/websocket/) - A collection of Django Channels WebSocket tutorials.
* [GeniePy](https://geniepy.com/blog/how-to-set-up-websockets-in-starlette/) - How to set up WebSockets in Starlette
* [Writing WebSocket servers (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_servers) - MDN guide to implementing the server side of the WebSocket protocol from scratch.
* [Writing WebSocket client applications (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_client_applications) - MDN reference for building browser WebSocket clients.
* [WebSocket (javascript.info)](https://javascript.info/websocket) - Clear, modern chapter on the browser WebSocket API with runnable examples.
* [Using WebSockets on Cloudflare Workers](https://developers.cloudflare.com/workers/examples/websockets/) - Official docs and example for handling WebSockets at the edge.

### Books

* [WebSocket](https://www.oreilly.com/library/view/~/9781449369262/) - Lightweight Client-Server Communications. Andrew Lombardi.
* [The Definitive Guide to HTML5 WebSocket](http://www.apress.com/gp/book/9781430247401) - Build Real-Time Applications with HTML5. By Vanessa Wang, Frank Salim, and Peter Moskovits. Source Code [here](https://github.com/Apress/def-guide-to-html5-websocket) ⭐ 12 | 🐛 0 | 📅 2017-10-16.
* [High Performance Browser Networking](https://hpbn.co/websocket/) - High Performance
  Browser Networking: WebSocket.

### Sites

* [WebSocket ORG](https://websocket.org) - The one-stop-shop for all your websocket needs.
* [WebSockets MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) - WebSockets Mozilla Developer Network (MDN).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/facundofarias/awesome-websockets/blob/master/CONTRIBUTING.md) ⭐ 1,858 | 🐛 5 | 📅 2026-08-17 before submitting your suggestion.

Feel free to [open an issue](https://github.com/facundofarias/awesome-websockets/issues) ⭐ 1,858 | 🐛 5 | 📅 2026-08-17 or [create a pull request](https://github.com/facundofarias/awesome-websockets/pulls) ⭐ 1,858 | 🐛 5 | 📅 2026-08-17 with your additions.

Thanks!

## Acknowledgments

Table of contents generated with [DocToc](https://github.com/thlorenz/doctoc) ⭐ 4,462 | 🐛 27 | 🌐 JavaScript | 📅 2026-08-04

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
