# new-obsidian-demo

A demo app to demonstrate the features of Obsidian 2.0

To try it out: 
1. Install the latest version of Deno  
2. Install the latest version of Redis to create an instance
3. Create a .env with:
```
PG_URI=[your postgres URI]
REDIS_HOST=localhost
```
4. Run the following script:
```
deno run --allow-env --allow-net --allow-read --unstable new-server.tsx -c tsconfig.json
```
