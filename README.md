# switch2jbnews
News relating to the switch 2 jailbreak

# Emulation is here!
Eglantine is the first working Switch 2 emulator. So far there are targeted builds for specific games and it is **very early** in development.

# History
Source: [pepsipu on ns2jb](https://pepsipu.com/blog/2026-10-switch2-jailbreak-ns2jb/)
## Beginnings
Shortly after Nintendo released the Switch 2 in June 2025, some crafty users found a game save exploit that was a proof of concept but not a full hack. Nothing much happened since then except a bunch of GBATemp and Reddit posts saying "The Switch 2 will never get hacked!"
## Getting Closer
In July 2026, developer Gezine, who had gained popularity by inventing Y2JB (youtube jailbreak) for the PS5, posted something on X showing a custom error code.
> "I created a Switch 1/2 userland exploit that is not a WebKit or save exploit.
>
> "But we already have a userland exploit from day one"
>
> The difference is that the existing userland exploit is based on the save exploit, which can't be used without save transfer using the Nintendo Online Service, which forces you to be on the latest firmware.
>
> So even if a kexploit or some software-based privilege escalation is found, 99% of people can't use the > save exploit. But this one works without any restrictions and works on all firmware.
>
> Why not hack WebKit? Switch 2 WebKit has ARM PAC (Pointer Authentication Code), which prevents ROP code execution. So I avoided it, as there was an easier way to exploit it."
> *— Gezine*
> <img width="486" height="274" alt="Screenshot from 2026-10-31 06-06-09" src="https://github.com/user-attachments/assets/0a259a2f-7ef2-40c1-9ccf-b8b0f0f384e8" />
## ns2jb
The homebrew floodgates got blown open by the new exploit released on October 22, 2026, when Sammy Hajhamid (a.k.a. **pepsipu**) released a softmod for the Switch 2. It is tethered and works if you have a special software called SmileBASIC 4. To perform it, you have to type in a bunch of random code and run a payload injector on an external device via NodeJS. The jailbreak is tethered and doesn't have coldboot protection. pepsipu demonstrated this with a video of _Mario Kart World_ with custom characters like Cinamoroll, Hatsune Miku, Peter Griffin, Goku, and Sans.

Watch the video [here](https://pepsipu.com/_astro/mario-kart-race-2-1080p.BwDXiEuM.mp4)
## Responses
### Nintendo
Within 7 hours of the jailbreak going public, Nintendo started pulling SmileBASIC 4 from the eShop. Some users found a way to download the delisted software by going to SmileBASIC's news channel on the news app, and get to the purchase screen. Nintendo has since patched this. They are actively working on a patch to stop the jailbreak and allegedly sent an email to Gezine.
### Gezine
Here are the quotes derived from X.
> "Talked with this guy. Seems legit. I think it was too early to burn the exploit. But kudos to him."
> 
> "I think it's possible to make untethered switch 2 jailbreak. Similar to Y2JB at PS5. We will see..."
> 
> "Smallbasic4 is not strictly needed. So I wouldn't update to latest firmware to get that game."
> "People seem to be confused about this. I meant that there’s an exploit based on a physical game cartridge. So you don’t have to update the firmware to use the eShop."
> 
> "I am pretty sure you don't have to worry about 'scalping exploit game' As there is something like M*g switch."
> 
> "Do people understand you can't transfer exploit save file without Nintendo online service? You need modded switch 1 too. You can't use artemis engine game to exploit without existing different exploit. Only buy save exploit based games if you know what you are doing."
> 
> "Bad news. I got email from Nintendo... 💀

## WebKit frontiers
pepsipu successfully ported ns2jb to the console's WebKit browser engine and after some beta testing, it is now released.
