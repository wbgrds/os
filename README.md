# Google Calendar Scheduling

Google Calendar Appointment Scheduling Integration

## Files

- `google-calendar-scheduling.css` - Button styles
- `google-calendar-scheduling.js` - Scheduling button loader

## Usage

### Include in HTML

```html
<link href="google-calendar-scheduling.css" rel="stylesheet">
<script src="google-calendar-scheduling.js" defer></script>
<script src="https://calendar.google.com/calendar/scheduling-button-script.js"></script>

<div id="cal"></div>

<script>
loadSchedulingButton('cal', 'YOUR_CALENDAR_URL', 'Rückruftermin', 'edit_calendar');
</script>
```

## Configuration

- `targetId` - HTML element ID where button renders
- `url` - Google Calendar scheduling URL
- `label` - Button label text
- `icon` - Material Icons name

## Fallback

If Google Calendar API unavailable, creates plain link button.
