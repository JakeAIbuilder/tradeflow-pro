# TradeFlow Pro 🔧

**AI-Powered Business Management Platform for Tradesmen**

A comprehensive business management platform designed specifically for tradesmen and service businesses. TradeFlow Pro helps you manage jobs, track leads, automate customer communications using AI, and optimize routes for maximum efficiency.

## 🚀 Features

### 💼 Job Management
- **Complete Job Tracking** - From initial inquiry to completion
- **Smart Scheduling** - Calendar integration with availability management
- **Client Management** - Store customer details, preferences, and history
- **Status Tracking** - Real-time updates on job progress

### 🎯 Lead Management
- **Lead Capture** - Automatic lead creation from multiple sources
- **Lead Scoring** - AI-powered lead qualification and prioritization
- **Conversion Tracking** - Monitor lead-to-job conversion rates
- **Source Attribution** - Track which marketing channels work best

### 🤖 AI Automation
- **Smart Responses** - AI-generated professional customer communications
- **Quote Generation** - Automated quote creation based on service requirements
- **Follow-up Management** - Intelligent scheduling of customer follow-ups
- **Message Templates** - Customizable templates for common scenarios

### 📊 Business Analytics
- **Revenue Tracking** - Real-time revenue and growth metrics
- **Performance Dashboard** - Key business metrics at a glance
- **Efficiency Reports** - Track time saved through automation
- **Conversion Analytics** - Monitor response rates and conversion metrics

### 🗺️ Route Planning
- **GPS Integration** - Real address geocoding and mapping
- **Route Optimization** - Efficient travel planning between job sites
- **Fuel Cost Estimation** - Calculate travel expenses automatically
- **Time Management** - Optimize schedules for maximum productivity

## 🛠️ Technology Stack

- **Frontend**: React 18 + TypeScript + Vite
- **Backend**: Node.js + Express + TypeScript
- **Database**: PostgreSQL with Drizzle ORM
- **UI**: Shadcn/ui + Tailwind CSS + Radix UI
- **AI**: OpenAI GPT-4o integration
- **State Management**: TanStack Query (React Query)
- **Routing**: Wouter for lightweight client-side routing
- **Forms**: React Hook Form + Zod validation

## ⚡ Quick Start

### Prerequisites
- Node.js 18+ installed
- PostgreSQL database (or use our in-memory storage for development)
- OpenAI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tradeflow-pro.git
   cd tradeflow-pro
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Add your API keys:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   DATABASE_URL=your_postgresql_connection_string
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   ```
   http://localhost:5000
   ```

## 🔧 Configuration

### Required Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `OPENAI_API_KEY` | OpenAI API key for AI features | Yes |
| `DATABASE_URL` | PostgreSQL connection string | Optional* |

*The app includes in-memory storage for development. For production, use PostgreSQL.

### Optional Environment Variables

| Variable | Description |
|----------|-------------|
| `WHATSAPP_ACCESS_TOKEN` | WhatsApp Business API access token |
| `WHATSAPP_PHONE_NUMBER_ID` | WhatsApp phone number ID |
| `WHATSAPP_WEBHOOK_VERIFY_TOKEN` | Webhook verification token |

## 📖 Usage

### Getting Started
1. **Dashboard Overview** - View your business metrics and recent activity
2. **Add Jobs** - Create new jobs with client details and scheduling
3. **Manage Leads** - Track potential customers and convert them to jobs
4. **AI Automation** - Set up automated responses and quote generation
5. **Route Planning** - Optimize your daily routes for efficiency

### Key Workflows
- **Lead to Job Conversion**: Leads → AI Response → Quote → Scheduled Job
- **Job Management**: Creation → Scheduling → Progress Tracking → Completion
- **Route Optimization**: Select jobs → Generate route → Export directions

## 🏗️ Architecture

```
tradeflow-pro/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Application pages
│   │   ├── hooks/         # Custom React hooks
│   │   └── lib/           # Utilities and configurations
├── server/                # Express backend
│   ├── routes.ts         # API route definitions
│   ├── storage.ts        # Data layer abstraction
│   └── services/         # Business logic services
├── shared/               # Shared types and schemas
└── docs/                 # Documentation
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Documentation**: Check our [docs](./docs/) folder
- **Issues**: Report bugs via [GitHub Issues](https://github.com/yourusername/tradeflow-pro/issues)
- **Discussions**: Join our [GitHub Discussions](https://github.com/yourusername/tradeflow-pro/discussions)

## 🎯 Roadmap

- [ ] WhatsApp Business API integration
- [ ] Advanced reporting and analytics
- [ ] Mobile app companion
- [ ] Multi-user team management
- [ ] Integration with accounting software
- [ ] Custom branding options

---

**Built with ❤️ for the trades community**
