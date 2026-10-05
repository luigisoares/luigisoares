## Luigi Soares

**Full-stack engineer shipping AI to production, on the edge.**
Durable workflows, serverless Postgres, and LLMs that have to be *right*, not just impressive.

<img src="https://skillicons.dev/icons?i=ts,svelte,cloudflare,postgres,react,tailwind,py" />

```jsonc
// wrangler.jsonc
{
  "name": "luigi",
  "main": "src/curiosity.ts",
  "compatibility_date": "2026-10-04",
  "workflows": [{ "name": "idea-to-prod", "class_name": "ShipItWorkflow" }],
  "durable_objects": { "bindings": [{ "name": "BRAIN", "class_name": "AlwaysLearningDO" }] },
  "hyperdrive": [{ "binding": "DB", "id": "neon-postgres" }],
  "r2_buckets": [{ "binding": "SIDE_PROJECTS", "bucket_name": "too-many" }],
  "observability": { "enabled": true } // "it worked locally" is not a metric
}
```

### What I build with

| | |
|---|---|
| **Edge** | Cloudflare Workers · Workflows · Durable Objects · R2 · Hyperdrive |
| **Data** | Postgres on Neon · Drizzle ORM |
| **API** | Hono · Zod + OpenAPI |
| **Front & mobile** | SvelteKit · Tailwind · Expo / React Native |
| **AI** | AI SDK · Claude · evals & tracing with Langfuse |
| **Shipping** | Turborepo + pnpm · Clerk · Stripe · Sentry · Vitest · Playwright · Biome |

### Lately

- 🧠 Long-running AI pipelines on Cloudflare Workflows: retries, fan-out, evals, real-time updates
- 🍳 **GastroOps**: a restaurant task app that has to be *simpler than paper*. Expo + Hono on Workers + Neon + R2

Currently making LLM pipelines boring. In the good way.

<sub>Off the clock: offline voice AI on my own GPU, and a Rust desktop assistant I talk to.</sub>
