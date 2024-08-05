# Spigot 是什么？

Spigot 是一个基于 Minecraft 的开源服务器软件，旨在优化性能和扩展功能。它支持 Bukkit 插件并且还提供了 Spigot API ，对插件提供多线程处理和高效的资源管理，兼容多个 Minecraft 版本。Spigot 具有易于配置的管理工具和活跃的社区支持，适合个人玩家和大型服务器管理员，确保游戏的安全性和公平性。

## 庞大的 Spigot 家族

::: details Spigot和她的孩子们（不完全）

```mermaid
graph LR
    Vanilla --> Bukkit
    subgraph Bukkit生态
        Bukkit --> Spigot
        subgraph Spigot生态
            Spigot --> Paper
            subgraph Paper分支
                Paper --> Pufferfish
                Paper --> Purpur
                Paper --> Magma
                Pufferfish --> Matter
                Paper --> Tuinity
                Tuinity --> Akarin
                Akarin --> Gale
                Purpur --> MultiPaper
                Paper --> Airplane
                Pufferfish --> Mirai
                Paper --> Gale
                Paper --> Folia
                Folia --> Kaiiju
                Paper --> PlazmaBukkit
                Paper --> EmpireCraft
                Paper --> Plazma
                Paper --> Slice
                Pufferfish --> JettPack
                Purpur --> Polpot
                Paper --> KTP
                Paper --> PandaSpigot
                Paper --> SparklyPaper
                Paper --> Petal
                Folia --> Luminol
                Paper --> Leaves
                Purpur --> KeYi
                Airplane --> Gale
                Purpur --> Gale
                Mirai --> Gale
                Kaiiju --> Gale
                Plazma --> Gale
                KeYi --> Gale
                EmpireCraft --> Gale
                Slice --> Gale
                Petal --> Leaf
                JettPack --> Gale
                SparklyPaper --> Leaf
                Leaves --> Leaf
                SparklyPaper --> Leaf
                PandaSpigot --> Leaf
                Matter --> Leaf
                KTP --> Leaf
                subgraph 整合分支
                    Gale --> Leaf
                    subgraph 再整合分支
                        Leaf
                    end
                end
            end
        end
    end
```

:::

由于很多服务端是分支，所以有很多配置文件是通用的。
