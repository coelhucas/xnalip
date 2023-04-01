I want to document this for myself so I can keep myself on track during the development

**Goals**
- make a tool for our personal usage completely compatible with windows, macOS, linux and consoles
- be as much compatible with both FNA and Monogame as possible, so we can change the backend for different platforms *if needed*
    * but every time we need to choose something, Monogame will have priority on being the "official xna core"
- only implement something if we need it
    * of course this only will be followed after I have the core engine handling basic stuff
- be completely opinative, based on how I like to do stuff, getting what was best for me from other tools I used
- get busywork that isn't relevant to my games out of the way (screen res, scene and object management, input from gamepad/kb, audio, handling graphics and setuping scenes)
- have control of our work at a lower level in a language we are decent at (C#)
- no public method should be added without proper documentation.
    * I can't remember what I had for lunch, I won't remember why I did shit this specific way

**Non-goals**
- Be something generic and ease to use for people outside our team
- Being a generic engine that's ease to reuse for any purposes (we want to iterate on it and improve during development, but not make it a jack of all trades)
- Compete with other engines. We just want to make things with our specific tools without relying much or 3rd parties that might have much breaking changes

## "in before"

### why are you doing this?
- I really like making tools. After that comes designing games, but for programming I find it most fun to make the game tools than the gameplay, for instance.
- I want to learn more in depth how engines works.
- People are so annoying about "how difficult this is" and "you shouldn't do that" that I want to do just as an opposite direction of this common belief of the game engine monster

### why not using X instead?
I spent many years having analisys paralisys about this stuff, I know C/C++ are the "cooler" way for some people, I personally wanted to use Rust but I really want to fuse my desire of creating this with the possibility of actually finishing something and getting money from it (I run [Softwool](https://softwool.co) and we need money to keep existing)

So XNA has been there for years, handle most of the more lower level stuff that I don't have time (sometimes even interest) of doing myself, so YMMV. I'm ok with that.

### you're not going to finish this
I imagine that this is a big probability, as soon as I make this notes public. Well, regardless, I've been studying and reading a lot, so even if I don't get anything practical, at least I enjoyed the process