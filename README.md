# 🧭 Trip-Planner Bot: Your AI Travel Buddy Powered by Langchain

## ✈️ What's This All About?

Say hello to **Trip-Planner Bot** — your AI-powered co-pilot for planning adventures! 🗺️ Built with the awesome **Langchain** framework and running on a snappy **Streamlit** interface, this bot is my first experimental dive into the world of Langchain and LLMs — a quick, scrappy build that turned out pretty cool!

This handy travel sidekick can help you:
- Discover cool stuff around you
- Learn about places
- Plan custom travel routes with waypoints, different transport modes, and more!

Whether you’re plotting a road trip or just fantasizing about one, Trip-Planner Bot’s got your back.

## 🧠 What Can It Do?

Using some nifty (and free!) APIs and a large language model, the bot brings the world to your screen. Here's the magic it can pull off:

- 📍 **Location Info Lookup**: Curious about a place? Ask the bot!
- 🗺️ **Explore Places Nearby**: Find local gems and hidden spots.
- 🛣️ **Plan Routes Like a Pro**: Get travel paths between multiple stops, by car, foot, or magic carpet (well, almost).

## 🔌 Powered by Some Cool APIs

Trip-Planner Bot isn’t working alone — it calls on a squad of APIs to work its magic:

- 🌍 **OpenStreetMap (via Geopy)** – For decoding location names into map-ready coordinates.
- 🧭 **Bing Maps** – Builds your travel routes with support for multiple stops and transport modes.
- 🗿 **FourSquare** – Helps you uncover trendy spots, from tourist attractions to taco joints.
- 📚 **Wikipedia (via Langchain)** – For all the juicy background info on places.

## 🧠 The Brain Behind the Bot

Running on **OpenAI’s GPT-3.5-Turbo**, this bot thinks fast and talks smooth. Feel free to swap in your favorite open-source LLM if you’re feeling adventurous.



## 🚀 How to Get Started

Wanna run it locally? Let’s go! 🏃‍♂️

1. Clone this repo:
    ```bash
    git clone https://github.com/adrija26sg/TRIPGPT
    cd TripplannerBot
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Fire up the app:
    ```bash
    streamlit run main.py
    ```

4. Click the link that shows up in your terminal and start planning your next adventure.

⚠️ **Heads-up**: Make sure your environment is set up with valid API keys for:
- OpenAI
- Bing Maps
- FourSquare

## 💡 Wanna Contribute?

Got ideas? Found a bug? Want to help this bot go from "quick and dirty" to "polished and legendary"? Fork this repo, drop a pull request, or open an issue — all contributions welcome!

## 🎥 Demo Time!

Check out this quick demo of the bot doing its thing:

[![Trip-Planner Bot Demo](demo uploaded soon)]

## ⭐ Show Some Love

If this bot helped you (or at least made you smile), please give the repo a ⭐️ — it means a lot!

---

Happy travels, fellow explorer! 🌍🧳💬
