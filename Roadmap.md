# Development Roadmap

## <span style="color:orange;">Phase 1: Foundation</span>

### Duration: 1-2 months.
#### Tasks:
- Set up a clean Debian CLI environment.
- Research and test tools for playback (e.g., mpv, ffmpeg) with HDR and 10-bit support.
- Configure HDMI audio passthrough and validate compatibility with Dolby Atmos.

## <span style="color:red;">Phase 2: Core Playback Features</span>
### Duration: 2-3 months.
#### Tasks:
- Implement local file playback.
- Set up integration with Jellyfin, Emby, and Plex APIs.
- Validate HDR video output and audio passthrough on target hardware.

## <span style="color:red;">Phase 3: Control System</span>
### Duration: 2-3 months.
#### Tasks:
- Build a fully functional web dashboard with playback controls.
- Add features to display current playback status, including:
- File name.
- Elapsed time and total duration.
- Implement scheduling, prerolls, and playlist management.
- Ensure playback commands are only available via the web interface.
- Configure kiosk mode for local GUI operation (if required).

## <span style="color:red;">Phase 4: Advanced Features</span>
### Duration: 2-3 months.
#### Tasks:
- Add logging and playback metrics.
- Optimize network performance for streaming.
- Include system resource monitoring tools.
- Provide customization options for HDR and audio settings.

## <span style="color:red;">Phase 5: Testing and Deployment</span>
### Duration: 1-2 months.
#### Tasks:
- Perform extensive testing on target hardware.
- Optimize performance for playback and streaming.
- Create deployment scripts for easy installation.

## <span style="color:red;">Phase 6: Post-Launch</span>
### Ongoing.
#### Tasks:
- Gather user feedback and implement improvements.
- Provide regular updates for compatibility with new media server versions.
- Explore support for additional features like live-streaming.