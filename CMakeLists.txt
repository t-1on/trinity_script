# Copyright (C) 2008-2012 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}

Custom/system/sec_anti_farming.cpp
Custom/system/chat_censure.cpp

Custom/Transmogrification.cpp
Custom/Transmogrification.h


Custom/events/Zombie_challenge/zombie_event.cpp
Custom/events/FFA_Zone/pvp_area.cpp
Custom/events/crypt_run/arena_event.cpp

Custom/general/npc_arena.cpp
Custom/general/npc_assistant.cpp
Custom/general/npc_beastmaster.cpp
Custom/general/npc_bountyhunter.cpp
Custom/general/npc_enchant.cpp
Custom/general/npc_event.cpp
Custom/general/npc_guildmaster.cpp
Custom/general/npc_lotto.cpp
Custom/general/npc_profession.cpp
Custom/general/npc_racechange.cpp
Custom/general/npc_summon.cpp
Custom/general/npc_support.cpp
Custom/general/npc_teleporter.cpp
Custom/general/npc_title.cpp
Custom/general/npc_tools.cpp
Custom/general/npc_trainer.cpp
Custom/general/npc_vote.cpp

custom/vendors/npc_gem.cpp
custom/vendors/npc_startergear.cpp
Custom/vendors/npc_weapon.cpp
Custom/vendors/npc_armor.cpp
Custom/vendors/npc_glyphs.cpp
Custom/vendors/npc_pvp_starter.cpp
Custom/vendors/npc_pve_starter.cpp
Custom/vendors/npc_allinone.cpp
Custom/vendors/npc_transmog_season.cpp
Custom/vendors/npc_transmog_tier.cpp
Custom/vendors/npc_transmog_weapon.cpp
Custom/vendors/npc_pve_end.cpp
Custom/vendors/npc_pvp_end.cpp
Custom/vendors/npc_donation.cpp
Custom/vendors/npc_profession_reagents.cpp
Custom/vendors/npc_mounts.cpp
Custom/vendors/npc_transmog_vip.cpp
Custom/vendors/npc_transmog_misc.cpp
Custom/vendors/npc_transmog_special.cpp

Custom/pvp/pvp_1v1.cpp
Custom/pvp/pvp_arena_spectator.cpp
Custom/pvp/pvp_blood_money.cpp
Custom/pvp/pvp_duel_reset.cpp
Custom/pvp/pvp_gold.cpp
Custom/pvp/pvp_killstreak.cpp

Custom/vip/vip_commands.cpp
Custom/vip/vip_only_vendor.cpp
Custom/vip/vip_only_area.cpp

Custom/world_chat.cpp
custom/arena_que.cpp
custom/item_gossip.cpp
custom/vip_buff.cpp
custom/item_gossip-old.cpp
custom/eventcommandscript.cpp
custom/horde_boss.cpp
custom/alliance_boss.cpp
custom/hva_control_npc.cpp

)

message("  -> Prepared: Custom")
