[project]
name = "a2a-sample-agent-medical-images"
version = "0.1.0"
description = "Medical image analysis agent with A2A Protocol using Gemini Vision and Tavily Search"
readme = "README.md"
requires-python = ">=3.12"
dependencies = [
"click>=8.1.8",
"httpx>=0.28.1",
"langchain>=0.3.0",
"langchain-community>=0.3.0",
"langchain-google-genai>=2.0.10",
"pydantic>=2.10.6",
"python-dotenv>=1.1.0",
"uvicorn>=0.34.2",
"sse-starlette>=2.3.6",
"starlette>=0.46.2",
"a2a-sdk>=0.3.0",
"tavily-python>=0.5.0",
]

[tool.hatch.build.targets.wheel]
packages = ["app"]

[build-system]
requires = ["hatchling"]
build-backend = "hatchling.build"
