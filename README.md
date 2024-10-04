# ゾンエスの銃プラグイン設定ファイルたち
## config.yml
```yml
ENABLE-DEBUG: false  # デバッグモードを有効にするかどうか
language: en  # 使用する言語（英語）
FriendlyFireEnabled: false  # チームメンバー同士で攻撃ができるかどうか
KickPlayerIfDeniedResourcepack: false  # リソースパックを拒否した場合にプレイヤーをキックするかどうか
useDefaultResourcepack: true  # デフォルトのリソースパックを使用するかどうか
EnableWeaponDurability: false  # 武器の耐久値を有効にするかどうか
BulletDetection:
  step: 0.1  # 弾丸の検出精度（数値が小さいほど高精度だが負荷が高い）
BlockBullets:
  door: false  # ドアが弾丸を遮るかどうか
  halfslabs: false  # ハーフスラブが弾丸を遮るかどうか
  leaves: false  # 葉が弾丸を遮るかどうか
  water: false  # 水が弾丸を遮るかどうか
  glass: false  # ガラスが弾丸を遮るかどうか
enableInteract:
  Chests: false  # チェストとのインタラクトを許可するかどうか
overrideAnvil: false  # 金床の動作を上書きするかどうか
showPossibleCrashHelpMessage: true  # クラッシュ時のヘルプメッセージを表示するかどうか
anticheatFix: false  # アンチチート対策を有効にするかどうか
verboseItemLogging: false  # 詳細なアイテムログを出力するかどうか
enable_permssionsToShoot: false  # 射撃に対して権限が必要かどうか
sendOnJoin: true  # 参加時にリソースパックを送信するかどうか
sendTitleOnJoin: false  # 参加時にタイトルを表示するかどうか
SecondsTillRPIsSent: 5.0  # リソースパックを送信するまでの時間
enableBulletTrails: true  # 弾道のトレイルを有効にするかどうか
BulletTrailsSpacing: 0.5  # 弾道のトレイル間のスペース
enableIgnoreArmorProtection: false  # 鎧の防御効果を無視するかどうか
enableIgnoreUnbreakingChecks: false  # "耐久力"エンチャントを無視するかどうか
enableIgnoreSkipForBasegameItems: false  # ゲーム内アイテムに対して特定のチェックを無視するかどうか
Items:
  enable_Unbreaking: true  # 武器に"耐久力"エンチャントを有効にするかどうか
enableReloadingOnDrop: false  # アイテムをドロップした時にリロードを開始するかどうか
enableReloadingWhenSwapToOffhand: true  # オフハンドに切り替えた際にリロードするかどうか
enableReloadOnlyWhenSwapToOffhand: false  # オフハンドに切り替えた時のみリロードするかどうか
allowGunHitEntities: false  # 銃でエンティティを攻撃できるかどうか
showOutOfAmmoOnTitle: false  # 弾切れをタイトルで表示するかどうか
showReloadingTitle: false  # リロード中のタイトルを表示するかどうか
showAmmoInXPBar: false  # 弾薬数をXPバーで表示するかどうか
perWeaponPermission: false  # 武器ごとに使用権限を設定するかどうか
enableExplosionDamage: false  # 爆発によるダメージを有効にするかどうか
enableExplosionDamageDrop: false  # 爆発によるアイテムドロップを有効にするかどうか
enablePrimaryWeaponLimiter: false  # プライマリ武器の制限を有効にするかどうか
weaponlimiter_primaries: 2  # プライマリ武器の最大所持数
weaponlimiter_secondaries: 2  # セカンダリ武器の最大所持数
enableCrafting: true  # 武器のクラフトを有効にするかどうか
enableShop: true  # ショップ機能を有効にするかどうか
AUTO-UPDATE: true  # 自動アップデートを有効にするかどうか
Swap-Reload-and-Shooting-Controls: false  # リロードと射撃の操作を入れ替えるかどうか
Order-Shop-By-Price: false  # ショップの並び順を価格順にするかどうか
enable_lore_gun-info_messages: true  # ロアに銃の情報メッセージを表示するかどうか
enable_lore_control-help_messages: true  # ロアに操作ヘルプメッセージを表示するかどうか
Enable_Headshot_Instantkill: true  # ヘッドショットで即死させるかどうか
Enable_Headshot_Notification_Sound: true  # ヘッドショット時の通知音を有効にするかどうか
Headshot_Notification_Sound: entity.experience_orb.pickup  # ヘッドショット時の通知音
Enable_Headshot_Sounds: true  # ヘッドショット音を有効にするかどうか
Enable_AutoArm_Grenades: false  # グレネードの自動装備を有効にするかどうか
gravityConstantForDropoffCalculations: 0.05  # 落下時の重力定数
allowGunReload: true  # 銃のリロードを許可するかどうか
Auto-Detect-Resourcepack: true  # リソースパックを自動検出するかどうか
ManuallyOverrideTo_1_8_systems: false  # 手動で1.8のシステムを使用するかどうか
ManuallyOverrideTo_1_13_systems: false  # 手動で1.13のシステムを使用するかどうか
ManuallyOverrideTo_1_14_systems: false  # 手動で1.14のシステムを使用するかどうか
unknownTranslationKeyFixer: false  # 不明な翻訳キーの修正を有効にするかどうか
Enable_Creation_Of_Default_Files: true  # デフォルトのファイル作成を有効にするかどうか
EnableGlowEffects: false  # 発光効果を有効にするかどうか
Break-Block-Texture-If-Shot: true  # ブロックが撃たれた際にテクスチャを破壊するかどうか
enableRecoil: true  # 銃の反動を有効にするかどうか
experimental:
  BulletWounds:
    InitialBloodLevel: 1500.0  # 負傷時の初期血量
    BloodIncreasePerSecond: 0.01  # 毎秒の血量増加率
    Medkit_Heal_Bloodloss_Rate: 0.05  # 救急キットの血量回復率
    enableBleeding: false  # 出血を有効にするかどうか
disableHotbarMessages:
  OutOfAmmo: false  # 弾切れ時のホットバー表示を無効にするかどうか
  Shoot: false  # 射撃時のホットバー表示を無効にするかどうか
  Reload: false  # リロード時のホットバー表示を無効にするかどうか
automaticallyReloadGunWhenOutOfAmmo: false  # 弾切れ時に自動的にリロードするかどうか
generalModifiers:
  sway:
    Run: 1.3  # 走っている時の揺れの倍率
    Walk: 1.5  # 歩いている時の揺れの倍率
    Ironsights: 0.8  # アイアンサイト使用時の揺れの倍率
    Sneak: 0.7  # しゃがんでいる時の揺れの倍率
deathmessages:
  enable: true  # 死亡メッセージを有効にするかどうか
impenetrableEntityTypes:
- ARROW  # 貫通しないエンティティのリスト
DefaultResourcepackOverride: false  # リソースパックの上書きを有効にするかどうか
IronSightsOnRightClick: false  # 右クリックでアイアンサイトを使用するかどうか
SwapSneakToSingleFire: false  # しゃがみを単発射撃に切り替えるかどうか
DestructableMaterials:
- MATERIAL_NAME_HERE  # 破壊可能な素材のリスト
RegenDestructableBlocksAfter: -1  # 破壊可能なブロックが再生成されるまでの時間（-1は再生成しない）
overrideAttackSpeed: true  # 武器の攻撃速度を上書きするかどうか
DefaultResourcepack: https://github.com/ZombieStriker/QualityArmory-Resourcepack/releases/download/latest/QualityArmory.zip  # デフォルトのリソースパックURL
```

## 銃コンフィグ
```yml
# 銃の名前(コマンドなどで使用)
name: ak47
# アイテムの表示名
displayname: '&6AK47'
# アイテムの耐久値(version<=1.13) or CustomModelData(version>1.13)
id: 5
# 同じアイテムデータで複数のアイテムを作成するときに使うバリアントタグ
variant: 0
# クラフト材料(list)
# [Material],[Durability],[Amount]
craftingRequirements:
- IRON_INGOT,0,15
- REDSTONE,0,5
# WeaponType は、作成する武器のクラスを決定します。銃の場合、これは重要ではありません。主に雑貨や防具に使われる。
weapontype: RIFLE
# 弾丸が撃たれたときに再生される音
weaponsounds: bulletmedium
# 再生するサウンドの音量
weaponsounds_volume: 4
# 照準機能(左手に持ちかえる)
enableIronSights: true
# 弾薬タイプ
# 初期値：「9mm」、「40mm」、「50bmg」、「556」、「762」、「fusion_cell」、「mininuke」、「muscketball」、「rocket」、「shell」
ammotype: '762'
# 被弾者に与えるダメージ
damage: 3
# 銃に込めれる弾数
maxbullets: 40
# ショップでの価格
price: 5000
# ■揺れ設定
# defaultValue: defaultの揺れ
# defaultMultiplier: 乗数
# unscopedModifier: 照準を使わなかった時の揺れ
sway:
  defaultValue: 0.19
  defaultMultiplier: 2
  unscopedModifier: 1
  sneakModifier: true
  moveModifier: true
  runModifier: true
# スニークしているときに銃を自動で表示する(?)
# firerate的に銃を自動発射させる?
isAutomatic: true
# isAutomaticがtrueの時に弾丸を発射する速度
firerate: 2
# 一度に発射される弾の数
bullets-per-shot: 1
# 反動が有効時にプレイヤーに適用される反動の量
recoil: 2.0
# 鈍足効果を使用して照準を合わせる際のプレイヤーの FOV を増加
# ※1以上に設定すると、プレイヤーにポーション効果が適用
setZoomLevel: 0
# 武器のリロードにかかる時間(秒単位)
delayForReload: 1.5
# プレイヤーが再び銃を撃つまでにかかる時間(秒単位)
delayForShoot: 0.3
# QAが計算を停止するまでの距離
maxBulletDistance: 200
# 銃の弾薬数を無制限にするかどうか
unlimitedAmmo: false
# LightAPI がサーバーにインストールされている場合、弾丸が発射されたときにプレイヤーに適用される光のレベルを制御します。
LightLeveOnShoot: 14
# BulletParticles、およびBulletParticles R、G、Bは、弾丸の軌跡として使用するパーティクルを決定します。REDSTONEを選択した場合、RGBを使用して使用する色を決定します。値の範囲は 0 から 1 で、既定値は白 (RGB= 1,1,1) です
particles:
  bullet_particle: REDSTONE
  bullet_particleR: 1
  bullet_particleG: 1
  bullet_particleB: 1
  bullet_particleData: 0
  bullet_particleMaterial: COAL_BLOCK
# ヘッドショットが発生したときにプレイヤーに適用される追加ダメージの量を制御します。デフォルトでは、元のダメージの3.5倍
headshotMultiplier: 3.5
invalid: false
durability: 1000
maxItemStack: 1
slownessOnEquip: 0
Version_18_Support: false
ChargingHandler: none
ReloadingHandler: none
addMuzzleSmoke: true
drop-glow-color: none
firing_knockback: 0
KilledByMessage: '%player% was shot by %killer% using a %name%'
DestructableMaterials:
- MATERIAL_NAME_HERE
lastModifiedByQA: 1719560543085
```
