# AIWorkspace

An intelligent project organization system that works with VS Code and Amazon Q to help you manage any type of project - from creative writing to application development.

## Features

- **Automatic Chat History**: Saves AI conversations for up to 30 days
- **User Preference Learning**: Analyzes your communication style and preferences
- **Smart Project Structure**: Creates logical directory structures based on your project type
- **Resource Integration**: Process and organize your reference materials
- **Human-Readable Files**: Everything saved in markdown format for easy editing

## How It Works

1. **Amazon Q Integration**: Uses `.amazonq/rules/` to automatically inject AIWorkspace behavior
2. **Memory System**: Tracks your preferences in `ai_system/memory/`
3. **Project Configuration**: Maintains settings in `ai_system/config/`
4. **Templates**: Provides starting structures for different project types in `ai_system/templates/`

## Getting Started

1. Open this folder in VS Code with Amazon Q extension installed
2. Start chatting with Amazon Q - it will automatically follow the AIWorkspace rules
3. Tell the AI about your project type and goals
4. Let the AI help you organize your project structure
5. Add resources to `project/user_resources/` folder for AI analysis

## Directory Structure

```
AIWorkspace/
├── .amazonq/rules/          # Amazon Q behavior rules
├── ai_system/               # System files (rarely accessed by users)
│   ├── memory/              # Chat history and user preferences
│   ├── config/              # Project settings
│   └── templates/           # Project structure templates
└── project/                 # Your workspace (main focus area)
    ├── user_resources/      # Your reference materials
    └── [project-files]      # AI-generated project structure
```

## Customization

- Modify `.amazonq/rules/aiworkspace.md` to change AI behavior
- Edit templates in `ai_system/templates/` folder
- Adjust settings in `ai_system/config/project_settings.md`

## Tips

- Use `@folder project/user_resources` to have AI analyze your materials
- Reference `@file ai_system/memory/user_preferences.md` to review learned preferences
- Focus your work in the `project/` folder - that's your main workspace
- Ask the AI to explain its organizational suggestions
- Request specific file templates for your project needs