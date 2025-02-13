# Create + Cobblemon MODPACK

## How to install

### Using Prism Launcher

1. create-pokemon.mrpack 다운
![1-1](image.png)
![1-2](image-1.png)
2. Prism Launcher 실행 > 인스턴스 추가
![2-1](image-2.png)
3. 불러오기 > 탐색하기
![3-1](image-7.png)
4. 검색 필터를 Zip archive(\*.zip, \*.zipx)에서 Modrinth 팩(\*.mrpack)으로 변경 > 다운받은 create-pokemon.mrpack를 선택 > 열기
![4-1](image-4.png)
![4-2](image-5.png)
5. OK
![5-1](image-6.png)
6. 선택적 모드는 모두 체크 해제 (현재 호환성 문제 발생) > OK
![6-1](image-8.png)

## How to reduce lag

필요한 만큼 이하의 항목을 수정하세요

### Distant Horizons 관련

32청크 이상의 매우 먼 거리를 렌더해주는 모드\
탁 트인 시야보다 성능이 중요한 경우 아래의 방법으로 조절/비활성화 가능

1. Esc > Options
2. 왼쪽 위 작은 버튼 >
3. LOD Render Distance Radius를 적당히 낮추거나 Quality Preset, CPU Load를 낮추세요
4. 편의에 따라 Enable Rendering을 False로 바꿔 아예 꺼버려도 됩니다

### 렌더 거리 관련

위 Distant Horizons를 비활성화하고도 렉이 심한 경우 제일 유효한 방법\
추가적으로 렌더 거리를 낮출 수 있다\
7청크까지는 보통 큰 불편함이 없으니 참고

1. Esc > Options
2. Render Distance를 낮추세요
3. 필요한 경우 Simulation Distance도 최하로 낮추세요

### 기타

여전히 불편한 경우 직접 프로파일링을 통해 렉을 많이 잡아먹는 모드를 찾을 수 있도록 spark라는 모드를 함께 설치해 두었음\

1. 월드에서 명령어 `/sparkc profile start`를 입력
2. 입력한 시점부터 플레이 과정에서의 리소스 사용량을 기록하기 시작한다
3. 적당한 시간이 지났을 시 `/sparkc profile open`을 입력
4. 약간 기다린 뒤(중간에 오류 표시가 뜰 수 있으나 무시) 채팅창에 뜨는 링크를 클릭 > Yes
5. 브라우저에서 mods 탭 선택
6. 그래프 아래쪽에 리소스 사용량 순서대로 모드가 정렬되어있음
7. 사용량이 높은 모드를 찾아서 적당히 설정
8. 이하의 모드들은 최적화 관련/필수 모드이므로 건드리지 말고 패스할 것
   1. Clumps
   2. Cull Less Leaves
   3. Dynamic FPS
   4. EntityCulling
   5. Fabricloader
   6. Fabric Lifecycle Events V1
   7. Fabric Renderer API V1
   8. Fabric Rendering V1
   9. Fabric Screen API V1
   10. FastQuit
   11. FerriteCore
   12. Hold That Chunk
   13. ImmediatelyFast
   14. Indium
   15. Iris\
   단, 쉐이더를 전혀 사용하지 않는다면 삭제 가능
   16. Krypton
   17. Language Reload
   18. Let Me Despawn
   19. Lithium
   20. Memory Leak Fix
   21. MixinTrace
   22. ModernFix
   23. More Culling
   24. Not Enough Crashes
   25. Puzzle
   26. PuzzlesLib
   27. Remove Reloading Screen
   28. Sodium
   29. Sodium Extra
   30. Sodium Shadowy Path Blocks
   31. spark
   32. VMP(Very Many Players)
   33. YOSBR

## Mod List

- [Let Me Despawn](https://modrinth.com/mod/vE2FN5qn) [1.2.0] by frikinjay
- [Traveler's Backpack](https://modrinth.com/mod/rlloIFEV) [1.20.1-9.1.9] by Tiviacz1337
- [ModernFix](https://modrinth.com/mod/nmDcB62a) [5.14.0+mc1.20.1] by embeddedt
- [Mouse Tweaks](https://modrinth.com/mod/aC3cM3Vq) [2.25] by Ivan Molodetskikh (YaLTeR)
- [Better Statistics Screen](https://modrinth.com/mod/n6PXGAoM) [3.9.3+fabric-1.20.1] by TheCSDev
- [Shulker Box Tooltip](https://modrinth.com/mod/2M01OLQq) [4.0.4+1.20.1] by MisterPeModder
- [Cobblemon Spawn Notification](https://modrinth.com/mod/LPuJjiQz) [1.4-fabric-1.3.0] by timinc aka Timothy Metcalfe
- [Continuity](https://modrinth.com/mod/1IjD5062) [3.0.0-beta.4+1.20.1] by PepperCode1
- [Double Doors](https://modrinth.com/mod/JrvR9OHr) [5.4] by Rick South
- [Dynamic FPS](https://modrinth.com/mod/LQ3K71Q1) [3.4.2] by juliand665, LostLuma
- [Universal Shops](https://pb4.eu) [1.3.2+1.20.1] by Patbox
- [ToolStats](https://modrinth.com/mod/vuGFx44e) [16.0.8] by Darkhax
- [FastQuit](https://modrinth.com/mod/x1hIzbuY) [3.0.0+1.20+] by KingContaria
- [Advancement Plaques](https://modrinth.com/mod/9NM0dXub) [1.4.11] by Grend
- [Prism](https://modrinth.com/mod/1OE8wbN0) [1.0.5] by Grend
- [Sodium Shadowy Path Blocks](https://modrinth.com/mod/EIa1eiMm) [3.2.1] by Rynnavinx
- [Simple Voice Chat](https://modrinth.com/mod/9eGKb6K1) [1.20.1-2.5.9] by Max Henkel
- [Clear Despawn](https://modrinth.com/mod/yoJJjRRE) [1.1.15] by StrikerRocker
- [Taterzens](https://modrinth.com/mod/vE972Kux) [1.11.7] by samo_lego
- [Create](https://modrinth.com/mod/Xbc0uyRg) [0.5.1-f-build.1335+mc1.20.1] by Fabricators of Create, Creators of Create
- [Drip Sounds](https://modrinth.com/mod/T8MMXTpr) [1.19-0.3.2] by PieKing1215
- [Krypton](https://modrinth.com/mod/fQEb0iXm) [0.2.3] by tuxed
- [Sound Physics Remastered](https://modrinth.com/mod/qyVF9oeo) [1.20.1-1.3.1] by Sonic Ether, vlad2305m, Max Henkel
- [Borderless Mining](https://modrinth.com/mod/kYq5qkSL) [1.1.8+1.20.1] by comp500
- [Botarium](https://modrinth.com/mod/2u6LRnMa) [2.3.3] by CodexAdrian
- [Entity Model Features](https://modrinth.com/mod/4I1XuqiY) [1.3] by Traben
- [AmbientSounds](https://modrinth.com/mod/fM515JnW) [5.3.9] by CreativeMD
- [Fabrishot](https://modrinth.com/mod/3qsfQtE9) [1.10.1] by ramidzkh
- [ToolTip Fix](https://modrinth.com/mod/2RKFTmiB) [1.1.1-1.20] by kyrptonaught
- [Iris Flywheel Compat](https://modrinth.com/mod/ndHYMY2K) [0.2.1] by Leon
- [Visual Workbench](https://modrinth.com/mod/kfqD1JRw) [8.0.0] by Fuzs
- [No Chat Reports](https://modrinth.com/mod/qQyHxfxd) [1.20.1-v2.2.2] by Aizistral
- [AdvancementInfo](https://modrinth.com/mod/G1epq3jN) [1.20-fabric0.83.0-1.4] by Giselbaer
- [Reese's Sodium Options](https://modrinth.com/mod/Bh37bMuy) [1.7.2+mc1.20.1-build.101] by FlashyReese
- [MixinTrace](https://modrinth.com/mod/sGmHWmeL) [1.1.1+1.17] by comp500
- [AppleSkin](https://modrinth.com/mod/EsAfCjCV) [2.5.1+mc1.20] by squeek502
- [Bookshelf](https://modrinth.com/mod/uy4Cnpcm) [20.1.9] by Darkhax
- [WorldEdit](https://www.curseforge.com/projects/225608) [7.2.15+6463-5ca4dff] by EngineHub
- [YOSBR](https://modrinth.com/mod/WwbubTsV) [0.1.2] by shedaniel
- [EnchantmentDescriptions](https://modrinth.com/mod/UVtY3ZAC) [17.0.14] by Darkhax
- [Create Slice & Dice](https://modrinth.com/mod/GmjmRQ0A) [3.1.0] by possible_triangle
- [Roughly Enough Professions](https://modrinth.com/mod/V8XJ8f5f) [2.0.2] by Mrbysco, ShyNieke
- [WaveyCapes](https://modrinth.com/mod/kYuIpRLv) [1.4.4] by tr7zw
- [Cardinal Components API](https://modrinth.com/mod/K01OU20C) [5.2.2] by UpcraftLP, Pyrofab
- [Cave Dust](https://modrinth.com/mod/jawg7zT1) [1.4.1] by LizIsTired
- [Forge Config API Port](https://modrinth.com/mod/ohNO6lps) [8.0.0] by Fuzs
- [Fadeless](https://modrinth.com/mod/ncKjyGm3) [1.0.1] by UltimateBoomer, DerpDerpling
- [FerriteCore](https://modrinth.com/mod/uXXizFIs) [6.0.1] by malte0811
- [Controlify](https://modrinth.com/mod/DOUdJVEm) [1.7.0-beta.1+1.20] by isXander
- [Boat Item View Fabric](https://modrinth.com/mod/BdKIyOLe) [0.0.5] by 50ap5ud5, Treblero
- [Highlighter](https://modrinth.com/mod/cVNW5lr6) [1.1.9] by Grend
- [Enhanced Block Entities](https://modrinth.com/mod/OVuFYfre) [0.9+1.20] by FoundationGames
- [Remove Reloading Screen](https://modrinth.com/mod/ZP7xHXtw) [3.2.0-1.20.1-fabric] by dima_dencep
- [EntityCulling-Fabric](https://modrinth.com/mod/NNAgCjsB) [1.6.2-mc1.20.1] by tr7zw
- [Fabric API](https://modrinth.com/mod/P7dR8mSH) [0.92.0+1.20.1] by FabricMC
- [Not Enough Crashes](https://modrinth.com/mod/yM94ont6) [4.4.7+1.20.1] by Fourmisain, Fudge, Liach, Madis0, Runemoro, Siuolplex, WuzgXY, the456gamer, wafflecoffee
- [Distant Horizons](https://modrinth.com/mod/uCdwusMi) [2.0.1-a]
- [LambDynamicLights](https://modrinth.com/mod/yBW8D80W) [2.3.2+1.20.1] by LambdAurora
- [Collective](https://modrinth.com/mod/e0M1UDsY) [7.40] by Rick South
- [Puzzle](https://modrinth.com/mod/3IuO68q1) [1.5.2+1.20] by PuzzleMC, Motschen
- [YetAnotherConfigLib](https://modrinth.com/mod/1eAoo2KR) [3.2.2+1.20] by isXander
- [Farmer's Delight](https://modrinth.com/mod/4EakbH8e) [1.20.1-1.4.3] by Zifiv, vectorwing, StevenPlayzz, dopadream, orlouge, BarchamMal, AwesomeDude091
- [CreativeCore](https://modrinth.com/mod/OsZiaDHq) [2.11.24] by CreativeMD, AriaFreeze
- [Lithium](https://modrinth.com/mod/gvQqBUqZ) [0.11.2] by JellySquid, 2No2Name
- [Roughly Enough Items](https://modrinth.com/mod/nfn13YXA) [12.0.684] by shedaniel
- [Better Ping Display](https://modrinth.com/mod/MS1ZMyR7) [1.1.1] by Quintinity
- [ImmediatelyFast](https://modrinth.com/mod/5ZwdcRci) [1.2.10+1.20.4] by RK_01
- [Chat Heads](https://modrinth.com/mod/Wb5oqrBJ) [0.10.32] by dzwdz, Fourmisain
- [e4mc](https://modrinth.com/mod/qANg5Jrr) [4.0.1] by skyevg
- [3d-Skin-Layers](https://modrinth.com/mod/zV5r3pPn) [1.6.2] by tr7zw
- [More Chat History](https://modrinth.com/mod/8qkXwOnk) [1.3.0] by JackFred
- [Capes](https://modrinth.com/mod/89Wsn8GD) [1.5.2+1.20] by Cael
- [Hold That Chunk](https://modrinth.com/mod/LXJlc5WJ) [2.0.1] by dlee13
- [Recipe Book Delight](https://modrinth.com/mod/cqC8Bgcm) [0.3.0-1.20] by melontini
- [Entity Texture Features](https://modrinth.com/mod/BVzZfTc1) [5.2.3] by Traben
- [Sodium Extra](https://modrinth.com/mod/PtjYWJkn) [0.5.4+mc1.20.1-build.115] by FlashyReese
- [spark](https://modrinth.com/mod/l6YH9Als) [1.10.53] by Luck
- [Debugify](https://modrinth.com/mod/QwxR6Gcd) [1.20.1+2.0] by isXander
- [Create](https://modrinth.com/mod/ysHf2zCJ) [0.5.1-d-build.1161+mc1.20.1] by Fabricators of Create, Creators of Create
- [FabricSkyBoxes](https://modrinth.com/mod/YBz7DOs8) [0.7.3+mc1.20.1] by AMereBagatelle
- [Cull Less Leaves](https://modrinth.com/mod/iG6ZHsUV) [1.3.0] by isXander
- [FabricSkyBoxes Interop](https://modrinth.com/mod/HpdHOPOp) [1.3.6+mc1.20.1-build.50] by FlashyReese
- [Eating Animation](https://modrinth.com/mod/rUgZvGzi) [1.20+1.9.5] by theone_ss, spusik_, PinkGoosik, DoctorNight1
- [Clumps](https://modrinth.com/mod/Wnxd13zP) [12.0.0.3] by Jaredlll08
- [NotEnoughAnimations](https://modrinth.com/mod/MPCX6s5C) [1.7.1] by tr7zw
- [Balm](https://modrinth.com/mod/MBAkmtvl) [7.2.2] by BlayTheNinth
- [Legendary Tooltips](https://modrinth.com/mod/atHH8NyV) [1.4.4] by Grend
- [Jade](https://modrinth.com/mod/nvQzSEkH) [11.8.0] by Snownee
- [Sodium](https://modrinth.com/mod/AANobbMI) [0.5.8+mc1.20.1] by @jellysquid3
- [Dynamic Crosshair](https://modrinth.com/mod/ZcR9weSm) [7.4.4+1.20] by Crendgrim
- [BetterF3](https://modrinth.com/mod/8shC1gFX) [7.0.2] by cominixo, TreyRuffy
- [Puzzles Lib](https://modrinth.com/mod/QAGBst4M) [8.1.17] by Fuzs
- [Language Reload](https://modrinth.com/mod/uLbm7CG6) [1.5.10+1.20.1] by Jerozgen
- [Indium](https://modrinth.com/mod/Orvt0mRa) [1.0.30+mc1.20.4] by comp500
- [Better Third Person](https://modrinth.com/mod/G1s2WpNo) [1.9.0] by Socolio, DreenDex
- [Xaero's Minimap](https://modrinth.com/mod/1bokaNcj) [23.9.7] by Xaero96
- [Waystones](https://modrinth.com/mod/LOpKHB2A) [14.1.3] by BlayTheNinth
- [Visuality](https://modrinth.com/mod/rI0hvYcd) [0.7.1+1.20] by PinkGoosik
- [Memory Leak Fix](https://modrinth.com/mod/NRjRiSSD) [1.1.5] by FX - PR0CESS
- [Fabric Language Kotlin](https://modrinth.com/mod/Ha28R6CL) [1.10.19+kotlin.1.9.23] by FabricMC
- [Zoomify](https://modrinth.com/mod/w7ThoJFB) [2.11.2] by isXander
- [Model Gap Fix](https://modrinth.com/mod/QdG47OkI) [1.14] by Mehvahdjukaar
- [Architectury](https://modrinth.com/mod/lhGA9TYQ) [9.2.14] by shedaniel
- [Cobblemon](https://modrinth.com/mod/MdwFAVRL) [1.4.1+1.20.1] by The Cobblemon Team
- [Factions Mod](https://modrinth.com/mod/ZjwW8Q6n) [2.5.1] by ickerio, BlueZeeKing, PyPylia
- [Bobby](https://modrinth.com/mod/bobby) [5.0.1] by johni0702
- [More Culling](https://modrinth.com/mod/51shyZVL) [1.20.4-0.22.1] by FX - PR0CESS
- [Falling Leaves](https://modrinth.com/mod/WhbRG4iK) [1.15.4] by Fourmisain, BrekiTomasson, RandomMcSomethin
- [Mod Menu](https://modrinth.com/mod/mOgUt4GM) [7.2.2] by Prospector, haykam821, TerraformersMC
- [Universal Shops](https://modrinth.com/mod/cnIatHrN) [1.3.2+1.20.1] by Patbox
- [Very Many Players](https://modrinth.com/mod/wnEe9KBa) [0.2.0+beta.7.102] by ishland
- [CIT Resewn](https://modrinth.com/mod/otVJckYQ) [1.1.3+1.20] by SHsuperCM
- [Cloth Config v11](https://modrinth.com/mod/9s6osm5g) [11.1.118] by shedaniel
- [Iceberg](https://modrinth.com/mod/5faXoLqX) [1.1.18] by Grend
- [Enhanced Attack Indicator](https://modrinth.com/mod/eTy17BBS) [1.0.4+1.20] by Minenash
- [Animatica](https://modrinth.com/mod/PRN43VSY) [0.6+1.20] by FoundationGames
- [Xaero's World Map](https://modrinth.com/mod/NcUtCpym) [1.37.8] by Xaero96
- [Voice Chat Interaction](https://modrinth.com/mod/qsSP2ZZ0) [1.20.1-1.0.6] by Max Henkel
- [Iris](https://modrinth.com/mod/YL57xq9U) [1.6.17] by coderbot, IMS212, Justsnoopy30, FoundationGames
- [InvMove](https://modrinth.com/mod/REfW2AEX) [0.8.4] by PieKing1215
- [Main Menu Credits](https://modrinth.com/mod/qJDfP7WN) [1.1.2] by isXander
- [Make Bubbles Pop Mod](https://modrinth.com/mod/gPCdW0Wr) [0.2.0-fabric] by Tschipcraft
- [Better Mount HUD](https://modrinth.com/mod/kqJFAPU9) [1.2.2] by Lortseam
