# Happy self-host image

Wrapper repository for building a Docker image of the Happy self-host server.

## Updating Happy

```bash
git -C app/happy fetch origin main
git -C app/happy checkout <commit>
git add app/happy
git commit -m "chore: bump happy"
git push
```
