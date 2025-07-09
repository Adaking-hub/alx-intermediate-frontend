#!/bin/bash

# Script to install Sass globally using npm

echo "👋 Starting setup..."

# Step 1: Check if Node.js is installed
echo "🔍 Checking for Node.js..."
if ! command -v node &> /dev/null; then
    echo "❌ Node.js is not installed. Please install it from https://nodejs.org"
    exit 1
else
    echo "✅ Node.js is installed. Version: $(node -v)"
fi

# Step 2: Check if npm is installed
echo "🔍 Checking for npm..."
if ! command -v npm &> /dev/null; then
    echo "❌ npm is not installed. Please install Node.js, which includes npm."
    exit 1
else
    echo "✅ npm is installed. Version: $(npm -v)"
fi

# Step 3: Install Sass globally
echo "📦 Installing Sass globally with npm..."
npm install -g sass

# Step 4: Check Sass version
echo "🔍 Checking Sass version..."
if command -v sass &> /dev/null; then
    echo "✅ Sass installed successfully! Version: $(sass --version)"
else
    echo "❌ Sass installation failed."
fi
echo "🎉 Setup complete! You can now use Sass in your projects."