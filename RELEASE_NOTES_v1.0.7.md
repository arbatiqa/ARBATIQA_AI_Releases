# ARBATIQA AI v1.0.7 Release Notes

**Release Date:** October 24, 2026  
**Status:** Official Production Release  
**Platform:** Windows 10/11 (64-bit)  
**File:** `ARBATIQA_AI_Setup_1.0.7.exe`  
**Size:** 191,550,047 bytes  
**SHA-256:** `8DEFCAD507A0D4126983C1707962808E398CB21D0C238A05BB5E1B39B9521788`  

## Key Features & Updates

### 1. Continuous Voice Assistant
- Continuous speech capture until microphone is clicked again.
- Dynamic 2-second silence timer: automatically transmits question once speech pauses for 2 seconds.
- Voice-activated "stop" command immediately cancels speech listening and resets the input flow.

### 2. Bilingual Text-to-Speech (TTS)
- Automatic vocalization of both questions and AI responses.
- Supports both English and Urdu with natural speech inflections.
- Sanitizes formatting artifacts (markdown asterisks, headers, emoji, punctuation symbols) before speaking.

### 3. Vector Speaker Mute Toggle
- Instant mute/unmute control beside the mic button.
- Clean red-cross indicator when muted.

### 4. Admin Version Telemetry
- Automatic reporting of installed application version (`v1.0.7`) and active timestamps (`last_seen_at`) on every login/session restore.
- Visible in the Supabase Admin Usage & Accounts panel.

### 5. Automated 3-Day Update Enforcement
- Automatically evaluates release publication dates.
- Informs users of new updates with a 3-day optional grace period.
- Strictly enforces installation after 3 days before allowing continued use.
- One-click verified download, checksum integrity verification, silent installation, and auto-restart.
