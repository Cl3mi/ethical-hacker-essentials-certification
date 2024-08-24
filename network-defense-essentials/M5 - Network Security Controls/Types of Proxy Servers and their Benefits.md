### What is a Proxy Server?

- **Definition**: 
  - A proxy server is a dedicated computer or software system that intermediates between internal devices and the internet.
  - It handles requests on behalf of other devices, retrieves the data from the internet, and sends it back to the requester.
  - Acts as a layer of defense and can help block malicious content and viruses.

### Benefits of Proxy Servers

- **Security**:
  - Blocks access to blacklisted sites.
  - Prevents exposure to sites known for distributing viruses.
- **Privacy**:
  - Hides internal IP addresses from external sources.
  - Prevents attackers from modifying cookies or browser configurations.
- **Performance**:
  - Caches frequently accessed websites, improving browsing speed.
- **Access Control**:
  - Allows for authentication, ensuring only authorized users can use the proxy.

### Functions of a Proxy Server

- **Request Handling**:
  - Receives requests from internal hosts and forwards them to the internet.
  - Modifies the request to mask the original source IP address.
  - Receives and checks the response against rules before sending it back to the internal host.
- **Types of Responses**:
  - **Successful**: Displays the requested content to the user.
  - **Blocked**: Indicates the site is restricted or unavailable.

### Components of Proxy Server Operation

- **Request**:
  - Client requests a webpage.
- **External Interface**:
  - Uses an external IP address to forward the request.
- **Response**:
  - The reply is sent back to the client after passing through the proxy server.

### Proxy Server vs. Packet Filter

- **Proxy Server**:
  - Inspects the payload of packets.
  - Creates detailed log files.
  - Restructures packets with a new source IP.
- **Packet Filter**:
  - Inspects routing information only.
  - Logs basic header information.
  - Allows or blocks packets without modifying them.

### Types of Proxy Servers

1. **Transparent Proxy**:
   - Invisible to end-users.
   - Requires manual client configuration.
   - Clients are unaware of its presence.

2. **Non-Transparent Proxy**:
   - Requires client software to be configured.
   - Clients are aware of the proxy server.
   - Can be complex to set up.

3. **SOCKS Proxy**:
   - IETF standard (RFC 1918).
   - Does not support caching.
   - Proxies connections without collecting data.

4. **Anonymous Proxy**:
   - Hides the user's IP address.
   - Allows anonymous browsing and bypasses internet censorship.
   - Potential downsides include slower speeds and legal issues in some countries.

5. **Reverse Proxy**:
   - Located near a server to handle requests to internal resources.
   - Used for content optimization and security.
   - Clients are unaware of its presence.

### Configuring a Proxy Server

- **Windows**:
  - Access through `Windows Key + I` > `Network & Internet` > `Proxy`.
  - Configure automatic or manual proxy settings.
- **Google Chrome/Edge**:
  - Access system proxy settings from within browser settings.

### Limitations of Proxy Servers

- **Security**:
  - The proxy server itself must be secured; otherwise, it can be a point of failure.
- **Workload**:
  - High workload can slow down performance due to extensive processing and caching.
- **Configuration**:
  - Incorrect settings can cause proxy malfunctions.
- **Performance**:
  - Initial loading of pages might be slow, and some pages might not load if bypassed.

### Example Tools and Servers

- **PF Sense Squid Proxy**:
  - Caches HTTP, HTTPS, and other protocols.
  - Configured through PF Sense for improved performance.
- **Proxy Tools**:
  - Whonix, Psiphon, Guardster, Proxify, ProxyCap, Fiddler, etc.