# 🎯 YT Analytics Backend

This is the backend service for the **YT Analytics** platform — a scalable and efficient API built with **FastAPI** and **TimescaleDB**, designed to handle large-scale, time-series data from YouTube video interactions in real-time.

## 📘 Overview

Modern video platforms track every interaction — play, pause, seek, hover — often within seconds. Now imagine 100,000 users doing that simultaneously. This backend is built to handle that scale using time-series optimized PostgreSQL via **TimescaleDB**.

By using **FastAPI**, **SQLModel**, and **Timescale**, we enable:
- Real-time ingestion of high-frequency events
- Scalable storage for millions of interaction logs
- Time-based aggregation for analytics & insights

## 🛠️ Tech Stack

- ⚙️ **FastAPI** – Lightweight, fast Python web API
- 🧠 **SQLModel** – ORM based on SQLAlchemy & Pydantic
- ⏱️ **TimescaleDB** – PostgreSQL extension for time-series data
- 🐳 **Docker** – Containerized development & deployment
- 🔌 **timescaledb-python** – Python client for Timescale features

## 🚀 Features

- Efficient logging of video events (play, pause, seek, etc.)
- Time-based analytics endpoint (e.g., views per second/minute)
- API-first design ready for frontend integration
- Scalable architecture with Docker support

