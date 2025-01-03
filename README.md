# Sample NextJS - Mindmap Copilot

Mindmap Copilot, powered by AI CopilotKit, simplifies your mindmap creation. Chat with your copilot to visualize and enrich your map with suggested notes for each node.

To learn more about how this project works, you can read this blog post: https://dev.to/ngviethoang/integrate-copilot-feature-into-your-react-applications-using-copilotkit-2nga

## 🚀 Getting Started  

### Open Using Daytona

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash
   daytona create https://github.com/daytonaio/sample-mindmap-copilot 
   ```
3. **Copy the `.env.example` file to `.env.local` file and edit it with your OpenAI API key:**
   ```bash
   OPENAI_API_KEY=<YOUR OPENAI API KEY>
   ```

4. **Start the Application**:
   ```bash
   npm run dev
   # or
   yarn dev
   ```  

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

## ✨ Features  

- **Interactive Visualization**: Adjust and add to your mindmap in real-time.
- **AI-Assisted Mindmap Creation**: Effortlessly create mindmaps by chatting with your AI Copilot.
- **Mindmap Q&A**: Ask anything about the mindmap content with your AI Copilot.
- **Note Suggestions**: Enrich your mindmap with AI-suggested notes.
- **Export Options**: Export your mindmaps in various formats for sharing or further use.

## Technology

- NextJS
- CopilotKit
- Typescript
- Tailwind
- Radix UI + icons
- Shadcn UI
- State Management: Zustand

## Demo

- Edit the mindmap and its style with the interactive UI



https://github.com/ngviethoang/MindmapCopilot/assets/25498258/4c9e2d87-18d1-4df1-bfc6-f4549c59dfbd



- Create mindmap by chatting with the Copilot



https://github.com/ngviethoang/MindmapCopilot/assets/25498258/9dcb1af2-bf41-4e67-b08d-65dda0e66eaf



- Do the Q&A with the Copilot about the current mindmap



https://github.com/ngviethoang/MindmapCopilot/assets/25498258/9d28c733-996a-46a7-a477-a756490595c9



- The copilot auto suggests more content when you are editing each node



https://github.com/ngviethoang/MindmapCopilot/assets/25498258/24585a73-b7d5-45f2-88d5-acddb081ba1d



