# SemanticNewsParser
Semantic news parser that runs directly in claude client, stores prompts for later. Must be run manually.

## Quick start
Paste this into any Claude conversation to recreate the tool. It will run directly in claude client, additions will be saved until you clear browser cache.

```
Create a web-based semantic news scanner React component that:

1. **Event Management**: Add/remove custom events to monitor (like "SpaceX Starship orbital test", "Company X earnings")
2. **Claude API Integration**: Uses Claude API to check if events occurred with structured JSON responses  
3. **Persistence**: Saves events, settings, and logs to localStorage across browser refreshes
4. **Smart Scheduling**: Configurable scan intervals, only checks events that haven't been checked recently
5. **Professional UI**: Dashboard with status counts, activity logs, start/stop controls
6. **Data Management**: Export/import functionality, clear all option

**Key Features:**
- Automated periodic scanning with Claude AI analysis
- Structured prompts asking for occurred: true/false with summaries
- Real-time status updates and logging
- Mobile-responsive interface
- Error handling and API rate limiting

Make it a complete, production-ready React artifact that handles everything automatically.
```

## 🔧 Customization Ideas

Users can modify the tool for:
- **Stock Events**: IPO announcements, earnings releases, stock splits
- **Tech Launches**: Product releases, software updates, company announcements  
- **Regulatory**: FDA approvals, policy changes, legal decisions
- **Personal**: Job postings, real estate listings, event announcements

## 💡 Pro Tips for New Users

1. **Start Small**: Begin with 2-3 events to test the system
2. **Be Specific**: Clear, specific queries work best ("Company X announces Series B funding" vs "Company X news")
3. **Check Intervals**: Use longer intervals for rare events, shorter for time-sensitive ones
4. **Export Data**: Regularly export your events as backup

## 🛠️ Advanced Usage

- **Team Sharing**: Export events and share JSON files with teammates
- **Multiple Instances**: Run different scanners for different categories
- **Integration**: Export occurred events for integration with other tools

## 📞 Support

This tool runs entirely in Claude - no external setup required!
For issues or enhancements, create a new Claude conversation and describe what you'd like to modify.

---

**Created for**: Monitoring uncertain-timing events with AI-powered news analysis  
**Platform**: Claude AI (claude.ai)  
**Requirements**: Modern web browser, Claude access
