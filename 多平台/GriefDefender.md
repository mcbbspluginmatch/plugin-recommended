
[align=center][size=5]GriefDefender[/size][/align][size=5]
[hr][indent][size=2][font=Tahoma]GriefDefender 的前身是 Sponge 版的 GriefPrevention，作为 Sponge 为数不多可用的领地插件存在。而现在，bloodmc 将他带到了 Bukkit 平台，我们很高兴能有幸目睹这一功能丰富的插件能在双平台上展现异样的光芒。

bloodmc 是 MCPC/Cauldron 的开发者之一，其代码老练、功能与性能兼具，后又混迹于 Sponge 社区。现在 GriefDefender 作为一个由混合端始祖之一开发的插件，自然也会支持混合端 (即 Bukkit + Forge)。

[color=Gray]由于 Mohist 破坏了 kyori-adapter 的实现，所以 GriefDefender 的 Raw 文本无法点击；LoliServer 继承了 Mohist 的部分代码，所以同样存在该问题。[/color]

[b]支持版本[/b]
[img]https://img.shields.io/spiget/tested-versions/68900?label=Bukkit[/img]
含 Sponge 1.12.2（在 2.0 版本前支持 Bukkit 1.8 ~ 1.16.5）

[b]社区评价[/b]
[img]https://img.shields.io/spiget/rating/68900?label=Spigot[/img]  [img]https://img.shields.io/github/stars/bloodmc/GriefDefender?label=Github[/img]

[b]相关地址[/b]
[url=https://www.spigotmc.org/resources/68900]Spigot[/url] [url=https://github.com/bloodmc/GriefDefender]Github[/url] [url=https://www.patreon.com/bloodmc]Patreon[/url] [url=https://github.com/bloodmc/GriefDefender/wiki]Wiki[/url] [url=https://github.com/bloodmc/GDHooks]GDHooks[/url]

[b]详细介绍[/b]
[spoiler][indent][b]广泛的支持[/b]
GriefDefender 作为领地插件，由于经历了 Sponge 时代的打磨，哪怕在 Bukkit/Hybrid 服务端上也有着对 Mod 一流的支持。这种支持十分恐怖，GriefDefender 能帮助您溯源 Forge 所提供的假玩家背后的真玩家 (基于假玩家的放置者)，其强大的标签系统允许您在 Mod 有 bug 的情况下使用 GriefDefender 提供的高级标签来读取 NBT/Meta 定义情境来 进行各种行为判断来阻止。

[b]用户友好性[/b]
它完全依赖 Raw 信息进行操作，但这并所有界面都已经被汉化 (包括预置标签)。相较于冗杂的 GUI，聊天框能更快速的处理您想要的一切。而在权限定义方面，GriefDefender 允许您创建 [b]领地群组[/b]，以便多个领地共享相同的领地配置，领地快照允许您保存当前设置状态，领地结构图则允许您快速把领地复原到某个时间点上的状况。

[b]高度客制化[/b]
功能性上，它能比肩 FTBChunk 但在客制化方面又超越 FTBChunk，它的标签系统允许您用最基础的标签创建属于您自己的标签来客制化保护体验。情境定义的对象包括但不限于 [b]领地、作用方块的数据、作用的玩家、作用的实体、权限[/b]，比如您可以让某个玩家被某个实体于某个领地之间没有碰撞箱。

[b]助力经济[/b]
在多样性方面，它支持领地的出租，出租后的领地租客挖掘领地内方块不会掉任何东西，而租期结束后领地又会自动复原。除此之外，您还能创建领地银行，征收领地税务，移除长期不活跃领地。在没有经济提供者 (Vault-Economy)，内置了名为 "领地方块" 的类货币机制，允许您通过玩家游戏时间奖励圈地方块。

[b]对管理员友善[/b]
您能为用户提供预制标签，也能通过权限给予玩家控制高级情境的能力。在情境定义方面，它支持 1.13+ 的 Tags 系统，这意味着您可以使用 #monster #player 代指一类事物以方便情境定义。

[b]强悍性能与多样的储存方式[/b]
GriefDefender 始终坚信，功能的冗杂并不代表性能的低效，GriefDefender 已经在超过 70+ 玩家的服务器中以 20 TPS 的佳绩稳定运行。数据库方面，支持 [b]MYSQL、MariaDB、PostgreSQL[/b]，如果您不使用数据库，GriefDefender 将使用 LuckPerms 和 文件 存储数据。

[b]主动兼容其他插件[/b]
在插件的支持上，GDHooks 涵盖了市面上大部分常见商店插件及在线地图插件 (Dynmap，Pl3xmap，Bluemap)，而对使用盔甲架的家具插件，我们更是直接挂钩家具库来识别家具类型，对 McMMO 的支持精确到了能否使用某个 Skill 。

[color=Gray]我这里无法再赘述太多，它还支持同客户端 mod CUI 的协同来显示领地，唯一的不足就是 GriefDefender 必须依赖一个支持情境系统的插件来储存数据（到目前为止只支持 LuckPerms）。[/color]

[img=500,0]https://i.loli.net/2021/10/03/OmxSB8uT3tjvHfM.gif[/img]

[img=500,0]https://i.loli.net/2021/10/03/wd3XWgsEyhGHmM9.gif[/img]
[/indent][/spoiler]
[color=Gray]本篇内容由 [u]ahdg[/u] 编写，[u]黑[/u] 整理。[/color]
[/font][/size][/indent][/size]