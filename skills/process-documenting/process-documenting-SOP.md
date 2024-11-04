#### **Title**: SOP - Process Documentation for Orlando Devs Website Refresh

#### **Purpose**:
To create a structured and comprehensive process for documenting development activities within the Orlando Devs Website Refresh Project. This SOP ensures all project-related work is recorded, transcribed, documented, and organized into skill-based articles. This approach enriches our AI-powered knowledge base, providing high-quality, reusable instructional content that supports training, onboarding, and knowledge sharing.

---

## **Contents**
1. **Overview of Documentation Process**
2. **Recording Guidelines**
3. **Transcription and Proofing**
4. **Instructional Article Creation**
5. **Skill-Article Generation**
6. **Sharing Documentation on Slack**
7. **Prompt Templates for AI-Generated Content**

---

### **1. Overview of Documentation Process**
Each time a contributor performs any significant task on the project—such as coding, attending meetings, or collaborating on design—they should:
1. **Record** their work, ideally with voice narration explaining key steps.
2. **Transcribe** the recording and proof the text for clarity.
3. **Generate** an instructional article explaining the process.
4. **Create** a skill-based knowledge article for AI training.
5. **Share** completed articles and recordings in the designated Slack channels.

---

### **2. Recording Guidelines**
- **Tool**: Use **Zoom** or other preferred recording software with local recording options.
- **Voice Narration**: Explain your actions and thought process as you work, using clear and concise language.
- **Content Types**:
  - **Individual Development**: Record coding tasks, design sessions, debugging, etc.
  - **Team Meetings and Collaboration**: Capture important discussions, brainstorming, and collaborative coding.
  - **Problem-Solving Sessions**: Document approaches to resolving bugs or implementing features.
- **Considerations**:
  - Keep screens clear of sensitive information.
  - Record audio to clarify the steps and ensure it’s usable for training purposes.

---

### **3. Transcription and Proofing**
Use **Otter.ai** or a similar transcription tool to create a written version of your recording. Proof the transcript to remove filler words and ensure technical accuracy.

---

### **4. Instructional Article Creation**
Once the recording and transcript are ready, generate an instructional article that explains the documented task. This article should be detailed enough to guide others through the process, making it a valuable training asset.

#### **Using the AI Engine to Create Instructional Content**:
1. **Open** the Orlando Devs Website Refresh Engineer AI Engine.
2. **Use the following prompt template**:

   ```
   "Generate an instructional article based on the following process: [Insert Process Description]. Explain the steps in an editorial, technical style, making the content accessible and informative for a new developer. Organize by process steps, include best practices, and emphasize clarity and detail. Target audience: team members learning the development process."
   ```

3. **Save** the article in `skills/web-application-developers-guide` directory within the repository as a Markdown file. If this directory doesn’t yet exist, create it.

---

### **5. Skill-Article Generation**
Skill-based articles ensure that the AI Engine retains structured knowledge about each task, which enhances its capacity to assist future contributors. 

#### **Creating a Skill-Article**
1. **Prompt the AI Engine** with this template:

   ```
   "Using the following transcript and instructional article, generate a Skill-Article that summarizes the process steps, highlights technical tasks, and breaks down key concepts for training purposes. Write it in a format that the AI Engine can use to improve response quality on similar topics. Title it as 'Skill-[SkillName]forOrlandoDevsAiEngine.md'."
   ```

2. **Save** the completed article in the `skills` directory. Use the naming format: `Skill-[SkillName]forOrlandoDevsAiEngine.md`.

---

### **6. Sharing Documentation on Slack**
Once the instructional and skill articles are ready, share a summary post in the `#contributor-guides` channel in Slack to make your documentation accessible to the team.

#### **Guidelines for Sharing**:
- **Post Title**: Include the skill or task covered (e.g., "Process Documentation Overview").
- **Brief Description**: Summarize the recorded content, instructional article, and skill-article.
- **Linking**: Attach links to the instructional article, skill-article, and the recording itself. If direct upload isn’t possible, upload the video to cloud storage and share a link.
- **Format Example**:
  
   ```
   **Title**: Process Documentation for [Task Name]
   **Description**: This covers [task details] with links to the instructional article, Skill-Article, and the screen recording. Designed to guide team members through our process documentation.
   - **Instructional Article**: [link]
   - **Skill-Article**: [link]
   - **Recording**: [link]
   ```

---

### **7. Prompt Templates for AI-Generated Content**
Below are prompt templates to use when interacting with the AI Engine for generating process documentation and skill articles. These templates ensure consistency in content quality and organization.

#### **Prompt for Instructional Article Generation**
   ```
   "Generate an instructional article for a [specific process or task]. The content should follow an editorial style, breaking down each step clearly. Structure the article for team members learning this process, with a focus on clarity, best practices, and thorough explanations. Organize by introduction, process steps, and key takeaways."
   ```

#### **Prompt for Skill-Article Creation**
   ```
   "Using the instructional article and transcript provided, create a Skill-Article summarizing the steps, highlighting key technical aspects, and providing an overview that the AI can use for training. Structure the content to optimize the AI’s ability to support team members on this topic in the future. Title the article 'Skill-[SkillName]forOrlandoDevsAiEngine.md'."
   ```

---

## **Conclusion**
By following this SOP, every team member can contribute to a rich knowledge base that serves current and future contributors. Each piece of documentation not only trains the AI Engine but also provides accessible learning resources, streamlining onboarding and enhancing team synergy. Our process documentation approach fosters an environment where contributors can learn from each other and drive continuous improvement through shared knowledge.

Let’s keep creating, learning, and growing together as we build a foundation for Orlando Devs’ future success.
