<div align="center">

# 🎬 video-transcript

## 音视频丢进去，带时间戳的逐字稿出来
## Audio or video in, timestamped transcript out

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

把上传的视频或音频整理成可阅读的带时间戳逐字稿。默认先用 ffmpeg 抽取并标准化音频，再调用内置 ASR 字幕生成作为主链路；只有在主 ASR 失败、结果无效或用户明确要求本地离线时，才启用 Whisper 兜底。除逐字稿和字幕源文件外，还能输出重点摘要、可复用金句库和结构化笔记。适用于视频字幕、播客转录、访谈整理和会议记录。

### ✨ 能做什么

- 先用 ffmpeg 抽取并标准化音频，再进入识别环节
- 内置 ASR 字幕生成作为主链路，优先保证速度
- 主 ASR 失败、结果无效或要求离线时，才启用 Whisper 兜底
- 输出带时间戳 Markdown、字幕源文件、重点摘要与可复用金句库
- 适用于视频字幕、播客转录、访谈整理与会议记录

### 📦 包含的技能

- `video-transcript` —— 见 [`video-transcript/SKILL.md`](video-transcript/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/video-transcript.git
cp -r video-transcript/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Converts uploaded video or audio into a readable timestamped transcript. Audio is extracted and normalized with ffmpeg first, then the built-in ASR subtitle generator runs as the primary path; local Whisper is reserved as an optional fallback for offline work or failed, unusable ASR results. Beyond the transcript and subtitle file, it can produce key-point summaries, reusable quote banks, and structured notes. Typical uses are video captions, podcast transcription, interview organization, and meeting records.

### ✨ What it does

- Extracts and normalizes audio with ffmpeg before any recognition runs
- Uses the built-in ASR subtitle generator as the primary path
- Falls back to local Whisper only when ASR fails, returns junk, or offline was requested
- Outputs timestamped Markdown, subtitle sources, key-point summaries, and quote banks
- Fits video captions, podcast transcription, interview notes, and meeting records

### 📦 Skills included

- `video-transcript` — [`video-transcript/SKILL.md`](video-transcript/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/video-transcript.git
cp -r video-transcript/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
