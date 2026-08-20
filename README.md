## Hi, I'm Oleksandr 👋

I build small, self-hosted pieces that make hardware I already own work better
together — mostly **home audio**, **Home Assistant**, and lately **LLM tooling**.
Everything below is Docker-first, multi-arch (amd64 + arm64), and rebuilt on a
schedule so security updates land without a commit.

---

### 🎵 Home audio

> **[Home Audio Stack](https://github.com/shuricksumy/home-audio-stack)** — start here.
> A map of how these fit together: Music Assistant → Snapcast → PipeWire, into USB
> DACs, Bluetooth speakers and LED strips.

| Project | |
| :-- | :-- |
| **[pipewire-snapclient](https://github.com/shuricksumy/pipewire-snapclient)** | Snapcast client + server on native PipeWire. Bit-perfect, no resampling on the way to the DAC. |
| **[bluetooth-web-snapclient](https://github.com/shuricksumy/bluetooth-web-snapclient)** | Pair Bluetooth speakers from a browser and run supervised Snapcast players on them. |
| **[pipewire-squeezelite](https://github.com/shuricksumy/pipewire-squeezelite)** | Squeezelite on PipeWire instead of an ALSA loopback — up to 384 kHz and DSD. |
| **[ledfx-snapcast-docker](https://github.com/shuricksumy/ledfx-snapcast-docker)** | Snapcast + Squeezelite + LedFx in one image, so WLED strips follow the music. |

### 🏠 Home Assistant

| Project | |
| :-- | :-- |
| **[home-assistant-apps](https://github.com/shuricksumy/home-assistant-apps)** | Add-ons that put services running on *other* hardware back in your sidebar, over Ingress. |
| **[wled-gateway-addon](https://github.com/shuricksumy/wled-gateway-addon)** | One WLED live-preview connection per device, fanned out to unlimited dashboard viewers. |

### 🤖 LLM tooling

| Project | |
| :-- | :-- |
| **[MCP-MusicAssistant](https://github.com/shuricksumy/MCP-MusicAssistant)** | An MCP server for Music Assistant — ask for music in a sentence, not an API call. |
| **[frigate-yard-stats](https://github.com/shuricksumy/frigate-yard-stats)** | Turns Frigate events into readable yard activity and vehicle reports. |

### 🔧 Infrastructure

| Project | |
| :-- | :-- |
| **[openvpn-ui](https://github.com/shuricksumy/openvpn-ui)** · **[docker-wgdashboard](https://github.com/shuricksumy/docker-wgdashboard)** | VPN management, containerised. |

---

<sub>Most of these started because something almost worked and the last 10% was
missing. If one of them saves you an evening, that's the point.</sub>
