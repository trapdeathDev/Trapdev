# SHARE BOOST

A powerful automation tool designed to increase the visibility of Facebook posts through automated sharing.

## Features

- **Automated Sharing**: Boost post visibility with configurable share amounts.
- **Session Management**: Track multiple sharing sessions simultaneously.
- **Real-time Progress**: Monitor share counts and status in real-time.
- **Modern UI**: Clean, responsive interface built with Tailwind CSS.
- **Cookie Support**: Supports standard Facebook cookies including `sb` and `datr`.

## Getting Started

### Prerequisites

- Node.js installed on your system.
- Valid Facebook cookies.

### Installation

1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

Start the development server:
```bash
node index.js
```
The application will be available at `http://0.0.0.0:5000`.

## How to Use

1. **Get Facebook Cookies**: Extract cookies from a logged-in Facebook session.
2. **Enter Post Details**: Paste the URL of the Facebook post you want to boost.
3. **Configure Settings**: Set the total share amount and interval between shares.
4. **Start Boosting**: Click "Start Sharing" and monitor progress in the dashboard.

## Security Note

Use longer intervals (30s+) and moderate share amounts to help keep your account safe from automated detection.

## License

MIT
