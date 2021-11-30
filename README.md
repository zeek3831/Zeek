- uses: lowlighter/metrics@latest
  with:
    # ... other options
    plugin_achievements: yes
    plugin_achievements_threshold: B      # Display achievements with rank B or higher
    plugin_achievements_secrets: yes      # Display unlocked secrets achievements
    plugin_achievements_display: compact  # Use compact display
    plugin_achievements_limit: 0          # Display all unlocked achievements (no limit)
    plugin_achievements_ignored: octonaut # Hide "octonaut" achievement
    plugin_achievements_only: explorer    # Display only "explorer" achievement (don't use with "ignored" option)
