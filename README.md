# dovado

Docker and dotnet running in a vagrant box. Useful for when you need to experiment with .net core in Docker, but can't install docker on the Windows machine (for instance, if it's Home edition).

## How to use

Clone the repository and set an ENV var to the source dir that you are going to be working on:

```bash
export dovado_source="../development/project"
```

Then bring it up:

```bash
./rebuild
```

It will automatically SSH into the box when done.

The box is on the private network at `192.168.33.10`.