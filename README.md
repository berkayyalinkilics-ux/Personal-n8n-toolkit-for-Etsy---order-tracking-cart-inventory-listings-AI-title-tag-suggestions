# n8netsy 🛒

Personal n8n automation toolkit for Etsy store management.

## 📋 Overview

This project contains n8n workflows designed for personal use to manage my Etsy shop more efficiently. It automates repetitive tasks and helps streamline daily operations.

## ✨ Features

- **Order Tracking** - Monitor and track order status automatically
- **Cart Management** - Manage shopping cart operations
- **Inventory Management** - Track stock levels and get alerts
- **Listing Optimization** - AI-powered title and tag suggestions for better SEO
- **Automation Workflows** - Reduce manual work with n8n automations

## 🔧 Technology Stack

- [n8n](https://n8n.io/) - Workflow automation platform
- [Etsy API v3](https://developers.etsy.com/) - Official Etsy Open API
- AI Integration - For smart title and tag generation

## 🔐 Data Privacy & Security

- This application is for **personal use only**
- No user data is collected or shared with third parties
- All API credentials are stored securely using n8n's credential management
- OAuth 2.0 is used for secure Etsy API authentication

## 📡 Etsy API Usage

This project uses the following Etsy API scopes:
- `transactions_r` - Read order/transaction data
- `listings_r` - Read shop listings
- `listings_w` - Update listings (titles, tags, inventory)
- `shops_r` - Read shop information

## 🚀 Setup

1. Import the workflow JSON files into your n8n instance
2. Configure Etsy OAuth credentials in n8n
3. Activate the workflows

## 📄 License

Personal use only. Not for redistribution.

---

**Author:** Personal Project  
**Purpose:** Etsy Shop Management Automation
