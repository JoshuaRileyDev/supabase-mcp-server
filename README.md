# Supabase MCP Server

A Model Context Protocol (MCP) server that provides programmatic access to the Supabase Management API. This server allows AI models and other clients to manage Supabase projects and organizations through a standardized interface.

<a href="https://glama.ai/mcp/servers/e994hfjjxc"><img width="380" height="200" src="https://glama.ai/mcp/servers/e994hfjjxc/badge" alt="Supabase Server MCP server" /></a>

## Features

### Project Management
- List all projects
- Get project details
- Create new projects
- Delete projects
- Retrieve project API keys

### Organization Management
- List all organizations
- Get organization details
- Create new organizations

## Installation
Add the following to your Claude Config JSON file
```
{
  "mcpServers": {
    "supabase": {
      "command": "npx",
      "args": [
        "y",
        "@joshuarileydev/supabase-mcp-server"
      ],
      "env": {
        "SUPABASE_API_KEY": "API_KEY_HERE"
      }
    }
  }
}
```
