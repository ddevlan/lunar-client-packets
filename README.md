# lunar-client-packets
Lunar-Client-Packets


# Packet ids and parameters
Format is: %packet_id% - %packet_name%(%parameters%)

```
0 - LCPacketClientVoice(?)
1 - LCPacketVoiceChannelSwitch(?)
2 - LCPacketVoiceMute(?)
3 - LCPacketCooldown(String name, long duration, int material)
4 - LCPacketHologram(UUID hologram, int x, int y, int z, String[] lines)
5 - LCPacketHologramUpdate(UUID hologram, String[] lines)
6 - LCPacketHologramRemove(UUID hologram)
7 - LCPacketNametagsOverride(UUID uuid, String[] tags)
8 - LCPacketNametagsUpdate(UUID uuid, String[tags]) (?)
9 - LCPacketNotification(?)
10 - LCPacketServerRule(?)
11 - LCPacketServerUpdate(?)
12 - LCPacketStaffModState(String mod, boolean state)
13 - LCPacketTeammates(UUID leader, long lastMs, UUID[] players)
14 - LCPacketTitle(?)
15 - LCPacketUpdateWorld(?)
16 - LCPacketVoice(UUID channel, byte[] data)
17 - LCPacketVoiceChannel(UUID channel, String name, UUID[] players, UUID[] listening)
18 - LCPacketVoiceChannelRemove(UUID channel)
19 - LCPacketVoiceChannelUpdate(int status, UUID channel, UUID uuid, String name)
20 - LCPacketWorldBorder(UUID id, UUID world, boolean cancels, boolean shrink, int color, int minX, int minZ, int maxX, int maxZ)
21 - LCPacketWorldBorderRemove(?)
22 - LCPacketWorldBorderUpdate(?)
23 - LCPacketWaypointAdd(?)
24 - LCPacketWaypointRemove(?)
25 - LCPacketGhost(?)
26 - LCPacketEmoteBroadcast(UUID uuid, int emoteId)
27 - LCPacketVersionNumber(?)
```
