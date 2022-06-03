### Mobile iPad Mirror Display
One thing we really enjoy at craft fairs is watching an artist work. Booth where the artist is melting glass in front of your face with a propane torch? Shut up and take my money!

Because Nukabelle works mostly on her IPad, we experimented with a few different ways of sharing her screen. At first, we tried APowerMirror, an app that allows you to screen share across two iPads. While it worked ok, the app would occasionally time out, forcing her to stop working and reset the app on both iPads. Not an ideal solution.

On DnD weekends, we usually load Roll20.net on an iPad and mirror it to the TV using Airplay. This works great, and we regularly leave it running for 4+ hours without any crashes/stuttering… it just works. The problem is, AppleTVs and devices that support Airplay video aren’t cheap.

In light of that, I decided some haxx0ring was in order. We loaded a Raspberry Pi with an Airplay emulator, then connected it to a monitor. Network connectivity is provided by a portable hotspot, and it’s all powered by a 222Wh 12V battery pack.

I’ll be doing a test this weekend; but according to the maths, we should get about 5 hours of stream time out of this setup.

### Parts List
- Monitor [Link]()
    - We picked this one because it uses a 12V @ 2.7A power supply, meaning we can plug it directly into the battery pack. This saves energy/weight/money by not requiring us to go from 12V DC > 110V AC > 12V DC.
    - The VESA mount holes should make it easy to mount to our grid wall as well.

- Battery Pack [Link]()
    - It was on sale on Amazon and had > 200Wh of power. We don’t stream the whole day, so it’s plenty for our needs.
    - If you pick something else, you’ll need to research the DC power output plug size and make sure you can get a cable that will connect to your monitor.

- Raspberry Pi [Link]()
    - Other “micro pc’s” exist and will probably work, but I had this one laying around the office. Follow [this tutorial]() to install the AirPlay emulator. It’s fairly straightforward and only took about 10 minutes to install.
    - Other AirPlay compatible HDMI devices like [this one]() are available if you don’t want to configure a Pi… but we’re trying to stretch our budget.
 
- Travel Wi-Fi Router [Link]() 
    -  Multi-purpose… when we’re in a hotel I can plug it into an Ethernet cable and share Wi-Fi easily… at the booth I just plug it into the battery pack and BAM! Reliable (offline) Wi-Fi.
    - Powered via Micro-USB; it fits with all my other 5V/12V gear
    - It also has the ability to connect via USB to a cellular modem; I haven’t tested that part out yet.

- 12V USB Adapter with multiple ports [Link]()
    - The battery pack came with a cigarette port adapter; this was an easy way to charge/power all our USB devices from a single place
    - Double bonus, I can run everything except the monitor from my car without risking the fuses

- 12V Extension Cable [Link]()
    - These let me place the battery pack somewhere 6+ feet away from the monitor.

- Right Angle HDMI Adapter [Link]()
    - With the HDMI ports on the back of the monitor, these adapters make things mount a little easier, as the cable now runs down towards the ground instead of directly out of the back.

### Finished Setup

Overall, I’m very happy with the way things worked out. Now, Nukabelle can be hard at work in the back, and customers can see what she’s working on.        
     