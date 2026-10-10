<p align="center">
  <img src="https://raw.githubusercontent.com/mojoto/.github/main/profile/assets/banner.png" alt="Mojoto — A fresh take on Mojo. Mojo flame meets mojito lime and mint." width="100%" />
</p>

<p align="center">
  Human-friendly libraries for <a href="https://www.modular.com/mojo">Mojo</a>.<br />
  Using Mojo should feel as refreshing as a mojito.
</p>

<p align="center">
  <a href="https://github.com/mojoto/morrow.mojo">Explore Morrow</a> &nbsp; · &nbsp;
  <a href="https://github.com/mojoto/req.mojo">Explore Req</a> &nbsp; · &nbsp;
  <a href="https://github.com/orgs/mojoto/repositories">All projects</a>
</p>

### A little less friction. A little more Mojo.

We build approachable tools for everyday programming in Mojo. From working with dates and times to making HTTP requests, our libraries keep common tasks readable and straightforward.

### Meet Morrow

**[Morrow.mojo](https://github.com/mojoto/morrow.mojo)** brings an Arrow-inspired date and time API to Mojo. Create, parse, format, shift, compare, and humanize date-time values with readable code.

```mojo
from morrow import Morrow

var morning = Morrow.get("2026-01-01 09:00:00Z")
print(morning.to("+08:00").format("YYYY-MM-DD HH:mm:ss ZZ"))
```

### Meet Req

**[Req.mojo](https://github.com/mojoto/req.mojo)** brings a native synchronous HTTP/1.1 client to Mojo. Make HTTPS requests with certificate verification, reuse connections, work with cookies and JSON, and stream downloads with a straightforward API.

```mojo
import req

def main() raises:
    var response = req.get("https://example.com")
    response.raise_for_status()
    print(response.text())
```

<p>
  <a href="https://github.com/mojoto/req.mojo/tree/main/website/docs"><strong>Documentation →</strong></a> &nbsp;&nbsp;
  <a href="https://github.com/mojoto/req.mojo#installation">Installation</a> &nbsp; · &nbsp;
  <a href="https://github.com/mojoto/req.mojo/releases">Releases</a>
</p>

### Make yourself at home

Found an edge case? Have a clearer example? Open an issue in [Morrow](https://github.com/mojoto/morrow.mojo/issues) or [Req](https://github.com/mojoto/req.mojo/issues), or send a pull request. Bug reports, documentation improvements, and small, thoughtful fixes are welcome.

---

<p align="center"><sub>A splash of Mojo. A squeeze of simplicity.</sub></p>
