# Experiment 2: TypeScript and Google Analytics Integration

This experiment demonstrates TypeScript concepts and Google Analytics integration.

## Part 1: TypeScript 

TypeScript provides typing and object-oriented features to JavaScript.

### Prerequisites

1. Node.js and npm installed on your system
2. TypeScript installed globally or locally
   ```
   npm install -g typescript
   ```

### Running TypeScript Examples

1. **Compile TypeScript to JavaScript**:
   ```
   tsc filename.ts
   ```

2. **Run the JavaScript file with Node.js**:
   ```
   node filename.js
   ```

## Part 2: Google Analytics Integration

Google Analytics is a web analytics service that tracks and reports website traffic.

### Files Included

1. **analytics.html** - Complete Google Analytics integration with explanations
2. **analytics-minimal.html** - Minimal version with just the essential tracking code

### How Google Analytics Integration Works

1. The tracking code loads the Google Analytics JavaScript library asynchronously
2. It initializes tracking with a unique measurement ID
3. It automatically sends pageview events when visitors load the page
4. Custom events can be tracked using the gtag() function

### Important Note

To use these examples with your own Google Analytics account:

1. Replace `G-MEASUREMENT_ID` with your actual Google Analytics measurement ID
2. Create a Google Analytics account at [analytics.google.com](https://analytics.google.com) if you don't have one
3. Your tracking data will be visible in the Google Analytics dashboard

### Testing the Integration

1. Open the HTML file in a browser
2. Use the Google Analytics Debugger browser extension to verify tracking
3. Custom events are triggered when clicking the "Track Event" button 