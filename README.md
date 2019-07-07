# lunar-client-packets
Lunar-Client-Packets


# Packet ids and parameters
Format is: %packet_id% - %packet_name%(%parameters%)

```
0 - LCPacketClientVoice(UUID channel, byte[] data)
1 - LCPacketVoiceChannelSwitch(?)
2 - LCPacketVoiceMute(?)
3 - LCPacketCooldown(String message, long duration, int material)
4 - LCPacketHologram(UUID hologram, int x, int y, int z, String[] lines)
5 - LCPacketHologramUpdate(UUID hologram, String[] lines)
6 - LCPacketHologramRemove(UUID hologram)
7 - LCPacketNametagsOverride(UUID uuid, String[] tags)
8 - LCPacketNametagsUpdate(Map<String, UUID> playersMap) (?)
9 - LCPacketNotification(String message, long duration, String level)
10 - LCPacketServerRule(String rule, int i, float f, boolean b, STring s)
11 - LCPacketServerUpdate(String server)
12 - LCPacketStaffModState(String mod, boolean state)
13 - LCPacketTeammates(long lastMs, UUID[] players)
14 - LCPacketTitle(String type, String message, double scale, long displayMs, long fadeInMs, long fadeOutMs)
15 - LCPacketUpdateWorld(UUID world)
16 - LCPacketVoice(UUID channel, String name, UUID[] players, UUID[] listening)
17 - LCPacketVoiceChannel(UUID channel, String name, UUID[] players, UUID[] listening)
18 - LCPacketVoiceChannelRemove(UUID channel)
19 - LCPacketVoiceChannelUpdate(int status, UUID channel, UUID uuid, String name)
20 - LCPacketWorldBorder(UUID world, boolean cancels, boolean shrink, int color, int minX, int minZ, int maxX, int maxZ)
21 - LCPacketWorldBorderRemove(UUID id)
22 - LCPacketWorldBorderUpdate(UUID id, int minX, int minZ, int maxX, int maxZ, int durationTicks)
23 - LCPacketWaypointAdd(String name, UUID world, int color, int x, int y, int z, boolean forced, boolean visible)
24 - LCPacketWaypointRemove(String name, UUID world)
25 - LCPacketGhost(UUID[] addGhostList, UUID[] removeGhostList)
26 - LCPacketEmoteBroadcast(UUID uuid, int emoteId)
27 - LCPacketVersionNumber(?)
```
