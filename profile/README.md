# The Web4 Foundation

About
-----

The Web4 Foundation is a nonprofit organization dedicated to the advancement of the open web through its fourth chapter: local-first, native webapps. The foundation is currently being organized as a 501(c)(6). Formal status is in progress.  Similar to organizations like W3C and WHATWG, the Web4 Foundation also stewards, defines, and extends the standards of the open web. However, its scope of influence is not targeted to browser vendors but rather to language communities. Web4’s directive is to support the implementation of these standards in execution contexts that run extramurally or adjacent to the core web browser – specifically edge servers and WebAssembly.

Repos
-----

The Web4 Foundation is an ecosystem of ecosystems.  Several repos are “no-code” repos and serve as a common area for all language communities to work together on issues, discussions, and documentation which then get implemented in dedicated SDK-repos, one for to each language community.

<table>
    <thead>
        <tr>
            <th>
                <h3>SDKs</h3>
                A monorepo for each language allowing each ecosystem to leverage its own idioms and tooling.
                <br /><br />
            </th>
            <th>
                <h3>Specs</h3>
                Specs, discussions, issues, and benchmarks.  Intentionally contains little or no implementation code.
                <br /><br />
            </th>
            <th>
                <h3>Tools</h3>
                Local-first applications require new capabilities across the traditional development stack.
                <br /><br />
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                Reference implementation
                <br /><br />
                <img src="https://brand.web4.dev/sdks/dotnet/dark/love.svg" style="width: 300px" />
                <br /><br />
                Contributors needed
                <br /><br />
                <img src="https://brand.web4.dev/sdks/java/dark/love.svg" style="width: 300px" /><br /><br />
                <img src="https://brand.web4.dev/sdks/go/dark/love.svg" style="width: 300px" /><br /><br />
                <img src="https://brand.web4.dev/sdks/kotlin/dark/love.svg" style="width: 300px" /><br /><br />
                <img src="https://brand.web4.dev/sdks/swift/dark/love.svg" style="width: 300px" /><br /><br />
                <img src="https://brand.web4.dev/sdks/javascript/dark/love.svg" style="width: 300px" /><br /><br />
                <img src="https://brand.web4.dev/sdks/ruby/dark/love.svg" style="width: 300px" /><br /><br />
                <img src="https://brand.web4.dev/sdks/python/dark/love.svg" style="width: 300px" /><br /><br />
                <p>
                    eXtramural Templating Markup Language – a hopeful W3C candidate recommendation for HTML6
                </p>
            </td>
            <td>
                <img src="https://brand.web4.dev/xtml/logo/dark.svg" style="width: 92px" />
                <p>
                    eXtramural Templating Markup Language – a hopeful W3C candidate recommendation for HTML6
                </p>
                <br /><br />
                <img src="https://brand.web4.dev/keyholes/logo/dark.svg" style="width: 92px" />
                <p>
                    A common abstraction for bridging into the DOM from WebAssembly or WebSockets
                </p>
                <br /><br />
                <img src="https://brand.web4.dev/htmlbench/logo/dark.svg" style="width: 92px" />
                <p>
                    A neutral testing ground for languages to compare their approaches for server-side rendering and reconciliation
                </p>
            </td>
            <td>
                <img src="https://brand.web4.dev/restful2/logo/dark.svg" style="height: 64px" />
                <p>
                    RESTful APIs over WebSockets instead of HTTP: `fetch()` → `listen()`
                </p>
                <br /><br />
                <img src="https://brand.web4.dev/syncql/logo/dark.svg" style="height: 64px" />
                <p>
                    Offline mode and query listeners with traditional SQL databases as the backing store
                </p>
                <br /><br />
                <img src="https://brand.web4.dev/systemui/logo/dark.svg" style="height: 64px" />
                <p>
                    A component library that mimics the look-and-feel of its surrounding OS – one app, multiple design systems
                </p>
            </td>
        </tr>
    </tbody>
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

Infrastructure for Edge Computing has reached an interesting tipping point recently where, thanks to geo-various datacenter buildouts, long-haul fiber installations, and even 5G rollouts, ubiquitous low latency has been achieved globally.  In a world where it’s possible to roundtrip to an edge server with lower latency than your screen’s own refresh rate, suddenly it makes sense to move a whole class of workloads off the client.  The architecture of these new edge-native opportunities are neither server-side, nor client-side, they are middle-out and must be local-first.

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
