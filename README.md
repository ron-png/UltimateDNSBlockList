# 🛡️ BigBlockList

**A balanced, high-performance DNS blocklist designed for a seamless web experience.**

![GitHub last commit](https://img.shields.io/github/last-commit/ron-png/BigBlockList)
![GitHub license](https://img.shields.io/github/license/ron-png/BigBlockList)

## 🚀 Overview

BigBlockList is an automatically updated aggregation of high-quality blocklists. I wanted to combine multiple "functionality over blocking" lists to create the ultimate fire and forget list. It aims to provide robust protection against ads, trackers, and malicious domains without breaking your favorite websites.

### 🎯 Philosophy

> **Usability First:** I believe that online protection shouldn't come at the cost of usability. This list is carefully curated to minimize false positives, ensuring that your internet works exactly as expected—just cleaner and safer.

## 📦 Sources

This list combines the following sources:

- **[AdGuard DNS Filter](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)**: A comprehensive filter composed of several other filters (AdGuard Base filter, Social Media filter, Tracking Protection filter, Mobile Ads filter, EasyList, and EasyPrivacy) specifically simplified to be compatible with DNS-level ad blocking.
- **[OISD Big](https://big.oisd.nl)**: A massive, highly-regarded blocklist that focuses heavily on not breaking valid services.

## 🔄 Updates

The list is automatically updated **every hour** to ensure the list stays up-to-date.

## 📥 Usage

**Raw URL:**
```
https://raw.githubusercontent.com/ron-png/BigBlockList/main/list/bigblocklist.txt
```

Add this URL to your Pi-hole, AdGuard Home, or any other DNS blocker.
