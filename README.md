# StudySphere

A centralized digital platform for competitive exam preparation, designed to bring study materials, AI-powered quizzes, performance analysis, and educational updates together in a single learning environment.

## Core Features

### Study Material Management

* **Centralized Learning Resources**

  * Subject-wise study materials
  * Organized content for competitive examinations
  * Dynamic access to learning resources
  * Notion-based content management
  * Easy access to updated study materials

### AI-Powered Quiz System

* **Intelligent Assessment**

  * AI-generated quiz questions
  * Topic-based quiz generation
  * Adaptive difficulty levels
  * Automated question generation using LLM services
  * AI-powered explanations for better conceptual understanding

### Quiz & Assessment

* **Interactive Quizzes**

  * Topic-wise quizzes
  * Real-time assessment
  * Instant result generation
  * Immediate feedback
  * Score tracking
  * Performance evaluation

### Performance Analysis

* **Learning Analytics**

  * Real-time performance tracking
  * Quiz score analysis
  * Strength and weakness identification
  * Assessment-based feedback
  * Progress monitoring
  * Data-driven learning insights

### News & Updates

* **Educational News**

  * Latest educational updates
  * Competitive exam-related news
  * Current affairs and relevant updates
  * News API integration
  * Centralized access to important information

### User Management & Security

* **Authentication & Authorization**

  * Secure user authentication
  * Role-Based Access Control (RBAC)
  * Student and administrator roles
  * Protected application resources
  * Secure data communication

### Responsive Learning Platform

* **Modern User Experience**

  * Responsive web interface
  * Interactive dashboards
  * Easy navigation
  * Cross-browser compatibility
  * Accessible across different devices

## Technologies Used

* **Frontend**: React, TypeScript, Vite
* **Backend**: RESTful APIs
* **AI & LLM**: LLM-based APIs for quiz generation and learning assistance
* **Content Management**: Notion
* **News Integration**: News API
* **Data Format**: JSON
* **Architecture**: Client–Server Architecture
* **Authentication**: Role-Based Access Control (RBAC)

## System Architecture

StudySphere follows a modular client–server architecture consisting of multiple interconnected components:

* **Frontend Module**

  * React-based user interface
  * TypeScript for type-safe development
  * Vite for optimized development and build processes

* **Application Module**

  * Core business logic
  * User authentication
  * Role-Based Access Control
  * Request and response processing

* **Content Management Module**

  * Notion integration
  * Dynamic study material access
  * Centralized content management

* **AI-Based Learning Module**

  * LLM-powered quiz generation
  * Adaptive difficulty assessment
  * AI-generated explanations

* **News Module**

  * News API integration
  * Educational and competitive exam updates

* **Performance Module**

  * Quiz evaluation
  * Real-time result generation
  * Performance analysis and feedback

## Application Workflow

1. User authenticates with the StudySphere platform.
2. The system provides role-based access to available features.
3. Students browse subject-wise study materials through the integrated content repository.
4. Students select topics and attempt interactive quizzes.
5. AI services can generate quizzes based on selected topics or content.
6. The system evaluates responses and generates results in real time.
7. Performance data is analyzed to identify strengths and areas for improvement.
8. Students can access relevant educational news and updates through the News module.

## Project Structure

```text
StudySphere/
├── frontend/
│   ├── src/
│   ├── public/
│   └── ...
├── backend/
│   ├── ...
│   └── ...
├── README.md
└── ...
```

> The project structure may vary depending on the current implementation.

## Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/ps589/studysphere.git
```

2. Navigate to the project directory:

```bash
cd studysphere
```

3. Install the required dependencies:

```bash
npm install
```

4. Create a `.env` file in the project root and configure the required API credentials.

5. Start the development server:

```bash
npm run dev
```

6. Open the local development URL displayed in the terminal.

## Environment Variables

Create a `.env` file in the root directory with the required configuration:

```env
VITE_API_URL=your_api_url
VITE_NOTION_URL=your_notion_url
VITE_AI_API_KEY=your_ai_api_key
VITE_NEWS_API_KEY=your_news_api_key
```


## Results

StudySphere was successfully implemented as an integrated web-based learning platform for competitive exam preparation.

* Average webpage loading time of under **1.5 seconds**
* Cross-browser testing across **Chrome, Firefox, and Edge**
* Real-time quiz result generation
* Instant assessment feedback
* Centralized study material access
* Dynamic AI-powered quiz generation
* Integrated educational news and updates
* Responsive and accessible learning environment

## Future Enhancements

* Personalized study plans
* Advanced learning analytics
* Expanded AI-based recommendations
* Additional competitive examination categories
* Personalized question difficulty adaptation
* More comprehensive mock examinations
* Progress visualization and dashboards
* Mobile application support

## Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create your feature branch:

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes:

```bash
git commit -m "Add some AmazingFeature"
```

4. Push the branch:

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request


   
