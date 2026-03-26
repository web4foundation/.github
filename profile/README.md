<br /><br /><br /><br />
<picture>
	<source srcset="https://brand.web4.dev/web4/header/dark.svg" media="(prefers-color-scheme: dark)">
	<img src="https://brand.web4.dev/web4/header/light.svg">
</picture>
<br /><br /><br /><br />

```html
<!-- MyButton.html -->

<script lang="C#">
    // 🚨🚨🚨  ⬆︎ ANY language!
    void OnClick(Event e)
    {
        c++;
    }
</script>

<button onclick={e => OnClick(e)}>
    Clicks:  {c}
    <!--🚨🚨🚨 ⬆︎ Reactivity as an HTML-primitive, no framework! -->
</button>

<!--
  Compile your HTML to...
    • a binary for multiplayer-reactivity + zero-cost dependencies  (mutates the DOM from the server)
    • WebAssembly for offline-reactivity + static hosting           (mutates the DOM from WASM)
-->
```

About
-----

The Web4 Foundation is a nonprofit organization dedicated to the advancement of the open web through its fourth chapter: local-first, native webapps. The foundation is currently being organized as a 501(c)(6). Formal status is in progress.  Similar to organizations like W3C and WHATWG, the Web4 Foundation also stewards, defines, and extends the standards of the open web. However, since Web4 executes extramurally instead of inside the browser, its scope of influence is not targeted towards browser vendors but rather towards language communities. Web4’s directive is to support the consistent implementation of these standards across all language communities to maximize skill-portability and minimize framework-fatigue.

Repos
-----

This GitHub org is organized to be an ecosystem of ecosystems.  Each repo fits into one of three categories.
1) **SDKs**<br />Each language community can build independently without the burden of conflicting conventions and idioms.
2) **Specs**<br />Contains no implementation code.  Used as a common area for cross-language discussions, issues, benchmarks, documentation, and specifications.  
3) **Tools**<br />Usually only implemented in one language – whichever is the best tool for the job.

### SDKs

<a href="https://github.com/web4foundation/web4-dotnet">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/dotnet/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/dotnet/light/love.svg" style="width: 300px">
    </picture>
</a>
&nbsp;&nbsp;&nbsp;(reference implementation)
<br /><br />
<a href="https://github.com/web4foundation/web4-java">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/java/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/java/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-go">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/go/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/go/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-kotlin">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/kotlin/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/kotlin/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-swift">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/swift/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/swift/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-javascript">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/javascript/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/javascript/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-ruby">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/ruby/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/ruby/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-python">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/python/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/python/light/love.svg" style="width: 300px">
    </picture>
</a>

### Specs

<table>
    <tr>
        <td style="min-width: 150px">
            <a href="https://github.com/web4foundation/xtml">
                <picture>
                    <source srcset="https://brand.web4.dev/xtml/logo/dark.svg" media="(prefers-color-scheme: dark)">
                    <img src="https://brand.web4.dev/xtml/logo/light.svg" style="width: 92px">
                </picture>
            </a>
            <p>
                eXtramural Templating Markup Language – a hopeful W3C candidate recommendation for HTML6
            </p>
        </td>
        <td style="min-width: 150px">
            <a href="https://github.com/web4foundation/keyholes">
                <picture>
                    <source srcset="https://brand.web4.dev/keyholes/logo/dark.svg" media="(prefers-color-scheme: dark)">
                    <img src="https://brand.web4.dev/keyholes/logo/light.svg" style="width: 92px">
                </picture>
            </a>
            <p>
                A common abstraction for bridging into the DOM from WebAssembly or WebSockets
            </p>
        </td>
        <td style="min-width: 150px">
            <a href="https://github.com/web4foundation/html-bench">
                <picture>
                    <source srcset="https://brand.web4.dev/html-bench/logo/dark.svg" media="(prefers-color-scheme: dark)">
                    <img src="https://brand.web4.dev/html-bench/logo/light.svg" style="width: 92px">
                </picture>
            </a>
            <p>
                A neutral testing ground for languages to compare their approaches for server-side rendering and reconciliation
            </p>
        </td>
    </tr>
</table>

### Tools

<table>
    <tr>
        <td style="min-width: 150px">
            <a href="https://github.com/web4foundation/restful2">
                <picture>
                    <source srcset="https://brand.web4.dev/restful2/logo/dark.svg" media="(prefers-color-scheme: dark)">
                    <img src="https://brand.web4.dev/restful2/logo/light.svg" style="height: 48px">
                </picture>
            </a>
            <p>
                RESTful APIs over WebSockets instead of HTTP<br /><code>fetch()</code> → <code>listen()</code>
            </p>
        </td>
        <td style="min-width: 150px">
            <a href="https://github.com/web4foundation/syncql">
                <picture>
                    <source srcset="https://brand.web4.dev/syncql/logo/dark.svg" media="(prefers-color-scheme: dark)">
                    <img src="https://brand.web4.dev/syncql/logo/light.svg" style="height: 48px">
                </picture>
            </a>
            <p>
                Operates similar to PgBouncer but enhances a subset of SQL for real-time query listeners and offline mode
            </p>
        </td>
        <td style="min-width: 150px">
            <a href="https://github.com/web4foundation/system-ui">
                <picture>
                    <source srcset="https://brand.web4.dev/system-ui/logo/dark.svg" media="(prefers-color-scheme: dark)">
                    <img src="https://brand.web4.dev/system-ui/logo/light.svg" style="height: 48px">
                </picture>
            </a>
            <p>
                A component library that mimics the look-and-feel of its surrounding OS – one app, multiple design systems
            </p>
        </td>
    </tr>
</table>

Why Web4?
---------

The story of the web is written in chapters not generations.  Generations replace what came before.  Chapters contribute to a single, holistic story.  Web1 was not replaced by Web2 and the intentions of Web3 was never to supplant the database.  Each new chapter coincides with the emergence of a new computing paradigm and its unique combination of constraints and superpowers that it unlocks.  From these new first principles, yesterday’s best practices become the new anti-patterns and a new species proliferates across the web.

| Chapter | Computing Paradigm | What it Enabled | Execution Location | Categories Unlocked |
|---|---|---|---|---|
| Web1 | Personal Computing | Static documents | Server-side | Long-form content<br /><sub>academic papers, news, blogs, marketing sites, etc</sub> |
| Web2 | Cloud Computing | Dynamic webpages | Client-side | Short-form content<br /><sub>e-commerce, social media, etc</sub> |
| Web3 | Decentralized Computing | Smart contracts | Peer-to-peer | Transactional content<br /><sub>DeFi, digital ownership, etc</sub> |
| Web4 | Edge Computing | Local-first apps | Edge-side / WASM | Function over content<br /><sub>utilities, games, collaborative, productivity, etc</sub> |

Infrastructure for Edge Computing has reached an interesting tipping point recently where, thanks to geo-various datacenter build-outs, long-haul fiber installations, and even 5G rollouts, ubiquitous low latency has been achieved globally.  In a world where it’s possible to roundtrip to an edge server with lower latency than your screen’s own refresh rate, suddenly it makes sense to move a whole class of workloads off the client.  The architecture of these new edge-native opportunities are neither server-side, nor client-side, they are middle-out and must be local-first.

### A New Species: Local-First Apps (LFA)

Local-first applications (LFA) emphasize function over content.  Typical categories include utilities, games, collaborative software, and productivity tools (categories far more prevalent in native app stores).  In this species, the concept of a “page” is eliminated entirely and URLs are used, not as locations of resources, but as bookmarks for state.  Local-first apps (LFA) differ from single-page apps (SPA) in a few fundamental areas:

|  | Single-page apps (SPA) | Local-first apps (LFA) |
|---:|---|---|
| Artifacts | Scripts | Binaries |
| State | Client-side | Extramural |
| Protocol | Request/response | Bidirectional |

### Core Benefits

- **Language Choice**<br />
  Web4 ends JavaScript’s monopoly on building dynamic user interfaces on the web.
- **Multiplayer Reactivity**<br />
  When application state lives on the server, multiple connected clients can react to the same state change.
- **Offline Reactivity**<br />
  Bidirectional protocols enable local-first synchronizations and apps continue to function even without a network connection.
- **Zero-Cost Dependencies**<br />
  When applications execute remotely, binaries can grow to gigabytes in size without impacting user experience because they are never transferred to the browser.

Get Involved
------------

The Web4 Foundation is an open collaboration between language communities, framework authors, and developers interested in advancing the web platform.

Ways to contribute:
- ⭐ Follow and star repositories to stay up to date.  Vote for your favorite language!
- 🐛 Report issues or suggest improvements
- 💬 Join discussions in spec repositories
- 🛠 Contribute code to language SDKs
- 📊 Help with benchmarks and interoperability testing
- 📚 Improve documentation and examples
