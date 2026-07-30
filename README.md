# AI-SDK

{
  "name": "agent-workflow-patterns",
  "version": "1.0.0",
  "description": "Five foundational AI agent workflow patterns built with the Vercel AI SDK",
  "main": "index.js",
  "type": "module",
  "scripts": {
    "pattern1": "npx tsx src/1-prompt-chaining.ts",
    "pattern2": "npx tsx src/2-routing.ts",
    "pattern3": "npx tsx src/3-parallelization.ts",
    "pattern4": "npx tsx src/4-orchestrator-worker.ts",
    "pattern5": "npx tsx src/5-evaluator-optimizer.ts",
    "all": "npx tsx src/run-all.ts"
  },
  "dependencies": {
    "ai": "^4.0.0",
    "@ai-sdk/anthropic": "^1.0.0",
    "zod": "^3.22.0"
  },
  "devDependencies": {
    "tsx": "^4.0.0",
    "typescript": "^5.0.0",
    "@types/node": "^20.0.0"
  }
}
