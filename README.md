# Amazon Consent with Didomi Web SDK

A sample application demonstrating the integration of Amazon Advertising System (AAS) with Didomi's Consent Management Platform (CMP) for GDPR compliance.

## Overview

This project integrates:

- **Amazon Advertising Tracking (AAT)**: For Amazon advertising pixel tracking
- **Amazon Consent Signal (ACS)**: For managing consent signals for Amazon ads
- **Didomi Web SDK**: For displaying consent notices and managing user privacy preferences

## Prerequisites

To use this application, you need:

1. **Didomi API Key**: Your organization's API key from Didomi
2. **Notice ID**: The ID of your configured consent notice in Didomi's Privacy Center

## Usage

### Running Locally

Open the `index.html` file in your browser with the required query parameters:

```
index.html?apiKey=YOUR_API_KEY&noticeId=YOUR_NOTICE_ID
```

## Error Handling

If you forget to include the required parameters, the application will:

- Log an error message to the browser console
- Display helpful information about the correct URL format
- Not load the Didomi SDK (preventing JavaScript errors)

Check your browser's developer console for error messages.
