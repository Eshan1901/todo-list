# todo-list
# 🚀 Todo List Pro

A modern, feature-rich todo list application built with pure HTML, CSS, and JavaScript. No frameworks required - just open and use!

![Todo List Pro](https://img.shields.io/badge/Version-1.0-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 🎯 **Core Task Management**
- **Add Tasks** - Create tasks with detailed information
- **Edit Tasks** - Click on any task to edit it inline
- **Complete/Undo** - Toggle task completion status
- **Delete Tasks** - Remove tasks with confirmation
- **Clear All** - Remove all tasks at once (with confirmation)

### 📊 **Organization & Prioritization**
- **Priority Levels** - High, Medium, Low with color coding
  - 🔴 High Priority (Red)
  - 🟡 Medium Priority (Orange)
  - 🟢 Low Priority (Green)
- **Categories** - Organize tasks by custom categories
- **Due Dates** - Set deadlines with overdue indicators
- **Smart Sorting** - Auto-sorts by priority and due date

### 🔍 **Advanced Filtering**
- **All Tasks** - View complete task list
- **Completed** - Show only finished tasks
- **Pending** - Show only incomplete tasks
- **High Priority** - Show only urgent tasks
- **Overdue** - Show only tasks past their due date

### 📈 **Statistics Dashboard**
- **Total Tasks** - Count of all tasks
- **Completed Tasks** - Progress tracking
- **Remaining Tasks** - Work left to do
- **Real-time Updates** - Stats update automatically

### 🎨 **User Experience**
- **Full-Page Layout** - Utilizes entire screen space
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Drag & Drop** - Reorder tasks by dragging
- **Glass Morphism** - Modern UI with backdrop blur effects
- **Smooth Animations** - Polished interactions throughout
- **Local Storage** - Tasks persist between sessions

### ⌨️ **Keyboard Shortcuts**
- **Enter** - Add new task
- **Escape** - Clear input field

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required!

### Installation
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start managing your tasks!

```bash
# Clone the repository
git clone [your-repo-url]

# Navigate to the directory
cd todo-list-pro

# Open in browser
open index.html
```

## 💻 Usage

### Adding a Task
1. Enter task description in the "Task Description" field
2. Select priority level (Low, Medium, High)
3. Add category (optional)
4. Set due date (optional)
5. Click "Add Task" or press Enter

### Managing Tasks
- **Complete**: Click the "Complete" button
- **Edit**: Click on the task text
- **Delete**: Click the "Delete" button
- **Reorder**: Drag and drop tasks

### Filtering Tasks
Use the filter buttons to view specific task subsets:
- **All** - Show all tasks
- **Completed** - Show finished tasks
- **Pending** - Show incomplete tasks
- **High Priority** - Show urgent tasks
- **Overdue** - Show overdue tasks

## 🎨 Visual Indicators

### Priority Colors
- **High Priority**: Red border and background tint
- **Medium Priority**: Orange border and background tint
- **Low Priority**: Green border and background tint

### Due Date Status
- **Overdue**: Red text for past due dates
- **Due Soon**: Orange text for tasks due within 24 hours
- **Normal**: Default color for future due dates

### Task Status
- **Completed**: Strikethrough text with reduced opacity
- **Pending**: Normal formatting

## 📱 Responsive Design

The application adapts to different screen sizes:

- **Desktop** (1200px+): Two-column layout with controls on left, tasks on right
- **Tablet** (768px-1199px): Single column with stacked layout
- **Mobile** (< 768px): Optimized for touch interaction

## 🛠️ Technical Details

### Built With
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid and Flexbox
- **Vanilla JavaScript** - No dependencies

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Data Storage
- Uses `localStorage` for data persistence
- Tasks automatically saved on every change
- Data survives browser restarts

## 📁 File Structure

```
todo-list-pro/
├── index.html          # Main application file
├── README.md          # This file
└── (optional files)
```

## 🔧 Customization

### Modifying Colors
Edit the CSS variables in the `<style>` section:
```css
/* Priority colors */
.priority-high { border-left-color: #e74c3c; }
.priority-medium { border-left-color: #f39c12; }
.priority-low { border-left-color: #2ecc71; }
```

### Adding New Categories
Categories are free-form text input. Common categories:
- Work
- Personal
- Shopping
- Health
- Education

### Changing Animations
Modify the animation durations in CSS:
```css
@keyframes fadeIn {
  /* Adjust timing as needed */
}
```

## 🚀 Performance

- **Fast Loading** - Single HTML file, no external dependencies
- **Lightweight** - Minimal code footprint
- **Smooth Animations** - Hardware-accelerated transitions
- **Efficient Storage** - Optimized localStorage usage

## 🔒 Privacy

- **100% Local** - All data stays on your device
- **No Tracking** - No analytics or tracking scripts
- **Offline Ready** - Works without internet connection

## 🐛 Troubleshooting

### Tasks Not Saving
- Ensure localStorage is enabled in your browser
- Check browser privacy settings
- Try refreshing the page

### Display Issues
- Update to latest browser version
- Disable browser extensions temporarily
- Check browser zoom level (recommended: 100%)

### Performance Issues
- Clear browser cache
- Close other browser tabs
- Restart browser

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📞 Support

If you encounter any issues or have questions:
1. Check the troubleshooting section above
2. Search existing issues
3. Create a new issue with detailed description

## 🎉 Acknowledgments

- Inspired by modern productivity applications
- Built with accessibility and usability in mind
- Designed for developers and productivity enthusiasts

---

**Enjoy organizing your tasks with Todo List Pro!** 🚀✨

*Made with ❤️ for productivity enthusiasts*
