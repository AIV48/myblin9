# API Specification

## Character Chat API

POST /api/chat

Request:
{
  "character_id": "sophie",
  "user_id": "user_001",
  "message": "Hello"
}

Response:
{
  "response": "Hi! Nice to see you again.",
  "memory_updated": true
}

---

## Memory Retrieval API

GET /api/memory/{user_id}

---

## AI Idol Profile API

GET /api/characters
