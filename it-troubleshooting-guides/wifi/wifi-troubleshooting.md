# Wi-Fi Troubleshooting Guide

## 1. Identify the Problem
- What SSID are you connected to?
- Are other devices affected?
- When did the issue start?

## 2. Check Layer 1 (Physical)
- Ensure Wi-Fi is on
- Check for loose cables on router
- Move closer to access point

## 3. Check IP & DHCP
- Run: `ipconfig`
- Verify IP address (should NOT be 169.x.x.x)
- Check gateway & DNS

## 4. Connectivity Tests
- Ping gateway
- Ping 8.8.8.8 (internet)
- Ping google.com (DNS)

## 5. Fixes
- Forget network → reconnect
- Reset adapter
- Release/renew IP:
  - `ipconfig /release`
  - `ipconfig /renew`

## 6. Escalate If
- Multiple users affected
- AP down
- ISP outage

## 7. Document
- Symptoms
- Steps taken
- Root cause

