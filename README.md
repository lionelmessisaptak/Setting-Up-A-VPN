# Task 8: VPN Setup and Privacy Analysis

## Objective
Understand how Virtual Private Networks (VPNs) protect privacy, encrypt internet traffic, and help mask real IP addresses. This task involves setting up a free VPN client, validating its functionality, and analyzing its impact on browsing speed and data protection.

---

## Tools Used

- **VPN Service:** ProtonVPN (Free Tier)
- **Operating System:** Windows 11
- **Web Browser:** Microsoft Edge
- **IP Check Tool:** [whatismyipaddress.com](https://whatismyipaddress.com)

---

## Task Guidelines (Hints)

1. Choose a reputable free VPN service and sign up.
2. Download and install the VPN client.
3. Connect to a VPN server (choose closest or any location).
4. Verify your IP address has changed (use whatismyipaddress.com).
5. Browse a website to confirm traffic is encrypted.
6. Disconnect VPN and compare browsing speed and IP.
7. Research VPN encryption and privacy features.
8. Write a summary on VPN benefits and limitations.

---

## VPN Setup Steps

### 1. VPN Service Selection
ProtonVPN was chosen due to its strong reputation, no data cap on the free tier, and commitment to user privacy.

### 2. Installation
- Downloaded ProtonVPN from the official website.
- Installed using default settings without any issues.

### 3. Connection
- Logged in using account credentials.
- Connected to the fastest free server available (Netherlands).

### 4. IP Address Verification

**Before VPN (Unprotected):**

- IP: `103.242.189.123`
- ISP: Alliance Broadband
- Location: Kolkata, India

![Unprotected IP]

**After VPN (Protected):**

- IP: `185.184.192.217`
- ISP: WorldStream B.V.
- Location: Naaldwijk, Netherlands

![Protected IP]

### 5. Traffic Encryption Test
Accessed various websites after VPN was connected — browsing was smooth, traffic was encrypted, and location masking was successful.

---

## Speed Comparison

| Condition         | Download Speed (approx.) | Upload Speed (approx.) | Server Location   |
|------------------|--------------------------|-------------------------|-------------------|
| Without VPN      | Faster                   | Faster                  | India             |
| With VPN         | Slightly Slower          | Slightly Slower         | Netherlands       |

*Note: VPN usage introduces some latency due to encryption overhead and server routing, which is normal for most VPN connections.*

---

## VPN Features and Encryption

- **Encryption:** AES-256, OpenVPN and WireGuard protocols.
- **Privacy:** No logs policy, DNS leak protection, and kill switch.
- **Free Plan Limitations:** Limited server selection, but no data cap.

---

## Summary: Benefits and Limitations of VPNs

### Benefits

- Encrypts internet traffic, preventing ISP and third-party tracking.
- Hides real IP address and location.
- Protects users on public Wi-Fi networks.
- Helps bypass geographical restrictions.

### Limitations

- Free servers may be slower due to high demand.
- Some websites block known VPN IPs.
- VPN does not prevent tracking via cookies or browser fingerprinting.
- Trust is required in the VPN provider’s privacy policy.

---

## Conclusion

ProtonVPN effectively masks the IP address and encrypts traffic, demonstrating the value of VPNs in securing online activity. Although free VPNs may have some limitations in speed and server options, they provide a strong foundation for privacy and security.
