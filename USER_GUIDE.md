# Recovery Missions — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.0.0.2** package linked in [this release](https://github.com/dafke1305/FS25_RecoveryMission/releases/tag/v1.0.0.2). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_RecoveryMission.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Choose a job and prepare

Open the normal **Contracts** screen for tow/recovery and roadside-service jobs. Accept for the farm that will do the work, then read its vehicle, fault, pickup and destination instructions. Bring your own suitable recovery or service equipment. This mod **does not include a winch**.

Default keyboard actions in this package:

| Action | Default |
| --- | --- |
| Accept/discover a hidden recovery | **Numpad Divide** (`/` on the numeric keypad) |
| Roadside/battery interaction | The **regular keyboard `/`**, not Numpad Divide |

F1 shows context-sensitive actions near an eligible target. Remap either action in **Controls** if necessary.

## Tow and roadside repairs

- For a tow job, recover the assigned stranded vehicle and take it to the specified workshop/delivery marker. Use the actual contract destination and wait for its completion/collection state.
- For roadside service, park a recognized service vehicle or mobile workshop from **your farm within 18 metres**. Approach the target and use the normal `/` action.
- With physical RMS/ADS equipment enabled and available, perform the indicated task: air tool for a tyre, grease gun for an engine job, or the specified equipment for a legacy battery job. Pressing `/` alone does not perform a physical tool repair.
- Without suitable RMS/ADS tools, supported jobs use the included timed service. Stay near the target until progress finishes. Optional departure behaviour may make the repaired vehicle leave before the contract completes.

## Replace a battery

1. Accept the battery-replacement job. Collect **that contract's new battery** at the vehicle shop/orange pickup marker and transport it to the stranded vehicle.
2. Stand on foot **in front of the vehicle, within one metre of its front edge**. Put carried objects down and select empty hands. Use regular `/` to remove the old battery and remain there during removal.
3. Put the removed old battery down. Carry the contract's **new** battery to the same front position and use `/` to fit it.
4. Remain close while the installation completes, following the current F1 prompt. Follow the job's final completion and reward instructions.

Wheel-replacement jobs on eligible tractors have their own spare-wheel pickup and mounting instructions. Follow those prompts; a tow job's broken axle/wheel is not automatically a spare-wheel service job.

## Hidden jobs, administrators and troubleshooting

Hidden recoveries are unannounced vehicles found while exploring. Approach one and use its **Accept hidden recovery** action, then recover it to the orange destination. Hidden completion pays its bonus automatically. Cancellation can cost **10%** of the assigned reward.

In **ESC > Game Settings > Recovery Missions - admin**, a logged-in administrator can configure generation, job limits, service/hidden jobs and rewards. Use **Save settings** to persist changes immediately. **Cancel all TFU jobs** removes job vehicles and can charge the assigned farms a 10% penalty for accepted jobs, including hidden jobs.

If no job generates, the slots may be full or the map may lack a suitable safe spawn/workshop. If service does not start, check the assigned farm, a recognized service vehicle, distance and the correct slash key. For a battery, also check front position, empty hands and that you carried the new contract battery rather than the old one.

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_RecoveryMission/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
