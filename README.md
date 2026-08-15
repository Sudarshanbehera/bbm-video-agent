# BBM Video AI Agent — Production Starter

## Goal
You enter a topic and the agent pipeline is designed to produce a finished video package:
Research → Script → Voice → Visuals → Editing → Captions → Quality/Safety → MP4.

## Important
This package is a production-oriented starter, not a finished hosted service. Real AI video
generation requires API/provider accounts, a backend worker, secure secret storage and FFmpeg.
The starter deliberately contains NO API keys.

## Run
### Windows
Use `run_windows.bat`

### macOS/Linux
Use `run_linux.sh`

Then open the local Streamlit address shown by the terminal.

## Production components to add
- LLM/research provider
- Text-to-speech provider
- Image/video generation or licensed stock provider
- FFmpeg render worker
- Object storage
- Job queue
- Database
- Authentication
- Rate limiting
- Monitoring
- Secure secret manager

## Output
The intended final output is an MP4 that you manually upload to YouTube/Instagram.

## Safety
- Do not invent sources.
- Verify sensitive claims.
- Medical/legal/political/crime allegations require human review.
- Do not use copyrighted media without permission.
- Do not impersonate real people or fabricate events.
