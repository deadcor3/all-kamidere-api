# all-kamidere-api
lua api in 1 page
# CBaseCombatWeapon
## Prop manipulations
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| int | GetPropInt | (int iOffset) | - |
| Vector | GetPropVector | (int iOffset) | - |
| float | GetPropFloat | (int iOffset) | - |
| bool | GetPropBool | (int iOffset) | - |
| string | GetPropString | (int iOffset) | - |
| void | SetPropInt | (int iOffset, int iNew) | - |
| void | SetPropVector | (int iOffset, Vector vecNew) | - |
| void | SetPropFloat | (int iOffset, float flNew) | - |
| void | SetPropBool | (int iOffset, bool bNew) | - |
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | IsDormant | () | - |
| int | GetClassId | () | - |
| Vector | GetMins | () | - |
| Vector | GetMaxs | () | - |
| float | GetNextPrimaryAttack | () | - |
| float | GetNextSecondaryAttack | () | - |
| bool | IsWeapon | () | - |
| float | GetSpread | () | - |
| float | GetInaccuracy | () | - |
| void | UpdateAccuracyPenalty | () | - |
| int | GetAmmo | () | - |
| int | GetAmmoReserve | () | - |
| int | GetViewModelIndex | () | - |
| int | GetWorldModelIndex | () | - |
| void* | GetWorldModelHandle | () | - |
| bool | IsReloading | () | - |
| int | GetItemDefinitionIndex | () | - |
| int | GetItemIDHigh | () | - |
| int | GetItemIDLow | () | - |
| int | GetAccountID | () | - |
| int | GetEntityQuality | () | - |
| bool | IsInitialized | () | - |
| string | GetCustomName | () | - |
| int | GetOwnerXuidLow | () | - |
| int | GetOwnerXuidHigh | () | - |
| int | GetFallbackPaintKit | () | - |
| int | GetFallbackSeed | () | - |
| float | GetFallbackWear | () | - |
| int | GetFallbackStatTrak | () | - |
# CBaseEntity
## Prop manipulations
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| int | GetPropInt | (int iOffset) | - |
| Vector | GetPropVector | (int iOffset) | - |
| float | GetPropFloat | (int iOffset) | - |
| bool | GetPropBool | (int iOffset) | - |
| string | GetPropString | (int iOffset) | - |
| void | SetPropInt | (int iOffset, int iNew) | - |
| void | SetPropVector | (int iOffset, Vector vecNew) | - |
| void | SetPropFloat | (int iOffset, float flNew) | - |
| void | SetPropBool | (int iOffset, bool bNew) | - |
## Static functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CBaseEntity* | GetLocalPlayer | () | - |
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | IsDormant | () | - |
| int | GetClassId | () | - |
| Vector | GetMins | () | - |
| Vector | GetMaxs | () | - |
| Vector | GetAbsOrigin | () | - |
| QAngle | GetAbsAngles | () | - |
| void | SetAbsOrigin | (Vector vecNew) | - |
| void | SetAbsAngles | (QAngle angNew) | - |
| int | GetMoveType | () | - |
| float | GetNextAttack | () | - |
| void* | GetActiveWeaponHandle | () | - |
| string | GetClassname | () | - |
| bool | IsPlayer | () | - |
| Vector | GetEyePosition | () | - |
| void | UpdateCollisionBounds | () | - |
| CBaseCombatWeapon* | GetWeapon | () | - |
| bool | IsEnemy | (CBaseEntity* pEntity) | - |
| bool | IsVisible | (CBaseEntity* pEntity, Vector vecSpot, bool bSmokeCheck) | - |
| bool | CanShoot | (CBaseCombatWeapon* pWeapon) | - |
| Vector | GetBonePosition | (int iBone) | - |
| Vector | GetHitboxPosition | (int iHitbox) | - |
| Vector | GetHitGroupPosition | (int iHitGroup) | - |
| QAngle | GetViewPunch | () | - |
| QAngle | GetPunch | () | - |
| Vector | GetViewOffset | () | - |
| float | GetFriction | () | - |
| int | GetTickBase | () | - |
| Vector | GetVelocity | () | - |
| Vector | GetBaseVelocity | () | - |
| void* | GetGroundEntityHandle | () | - |
| int | GetHealth | () | - |
| int | GetLifeState | () | - |
| float | GetMaxSpeed | () | - |
| int | GetFlags | () | - |
| int | GetObserverMode | () | - |
| void* | GetObserverTargetHandle | () | - |
| void* | GetViewModelHandle | () | - |
| int | GetEFlags | () | - |
| float | GetSurfaceFriction | () | - |
| int | GetShotsFired | () | - |
| int | GetMoney | () | - |
| int | GetTotalHits | () | - |
| int | GetArmor | () | - |
| QAngle | GetEyeAngles | () | - |
| bool | IsDefusing | () | - |
| bool | IsScoped | () | - |
| bool | IsGrabbingHostage | () | - |
| bool | IsRescuing | () | - |
| bool | HasHelmet | () | - |
| bool | HasHeavyArmor | () | - |
| bool | HasDefuser | () | - |
| bool | HasImmunity | () | - |
| bool | IsInBuyZone | () | - |
| float | GetFlashAlpha | () | - |
| float | GetFlashDuration | () | - |
| int | GetGlowIndex | () | - |
| float | GetLowerBodyYaw | () | - |
| int | GetSurvivalTeam | () | - |
| int | IsUsedNewAnimState | () | - |
| float | GetAnimationTime | () | - |
| float | GetSimulationTime | () | - |
| float | GetOldSimulationTime | () | - |
| Vector | GetOrigin | () | - |
| QAngle | GetRotation | () | - |
| int | GetTeam | () | - |
| void* | GetOwnerEntityHandle | () | - |
| int | GetCollisionGroup | () | - |
| bool | IsSpotted | () | - |
# CConVar
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| string | GetName | () | - |
| float | GetFloat | () | - |
| int | GetInt | () | - |
| bool | GetBool | () | - |
| string | GetString | () | - |
| void | SetString | (string szNew) | - |
| void | SetFloat | (float flNew) | - |
| void | SetInt | (int iNew) | - |
# CUserCmd
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| int | iCommandNumber | - |
| int | iTickCount | - |
| QAngle | angViewPoint | - |
| Vector | vecAimDirection | - |
| float | flForwardMove | - |
| float | flSideMove | - |
| float | flUpMove | - |
| int | iButtons | - |
| byte | uImpulse | - |
| int | iWeaponSelect | - |
| int | iWeaponSubType | - |
| int | iRandomSeed | - |
| short | sMouseDeltaX | - |
| short | sMouseDeltaY | - |
| bool | bHasBeenPredicted | - |
| Vector | vecHeadAngles | - |
| Vector | vecHeadOffset | - |
# IGameEvent
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| string | GetName | () | - |
| bool | GetBool | (string szKeyName) | - |
| int | GetInt | (string szKeyName) | - |
| uint64 | GetUint64 | (string szKeyName) | - |
| float | GetFloat | (string szKeyName) | - |
| string | GetString | (string szKeyName) | - |
| void | SetBool | (bool bNew) | - |
| void | SetInt | (int iNew) | - |
| void | SetFloat | (float flNew) | - |
| void | SetString | (string szNew) | - |
# INetChannelInfo
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| string | GetName | () | - |
| string | GetAddress | () | - |
| float | GetTime | () | - |
| float | GetTimeConnected | () | - |
| int | GetBufferSize | () | - |
| int | GetDataRate | () | - |
| bool | IsLoopback | () | - |
| bool | IsTimingOut | () | - |
| bool | IsPlayback | () | - |
| float | GetLatency | (EFlow flow) | - |
| float | GetAvgLatency | (EFlow flow) | - |
| float | GetAvgLoss | (EFlow flow) | - |
| float | GetAvgChoke | (EFlow flow) | - |
| float | GetAvgData | (EFlow flow) | - |
| float | GetAvgPackets | (EFlow flow) | - |
| int | GetTotalData | (EFlow flow) | - |
| int | GetTotalPackets | (EFlow flow) | - |
| int | GetSequenceNr | (EFlow flow) | - |
| bool | IsValidPacket | (EFlow flow, int nFrame) | - |
| float | GetPacketTime | (EFlow flow, int nFrames) | - |
| int | GetPacketBytes | (EFlow flow, int nFrames, int group) | - |
| float | GetTimeSinceLastReceived | () | - |
| float | GetCommandInterpolationAmount | (EFlow flow, int nFrames) | - |
| float | GetTimeoutSeconds | () | - |
# PlayerInfo
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| bool | bFakePlayer | - |
| string | szName | - |
| string | szSteamID | - |
| int | nUserID | - |
| int64 | ullXuid | - |
| int | nXuidLow | - |
| int | nXuidHigh | - |
# Color
## Constructors
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| Color | new | (float r, float g, float b, float a) | float values from 0.0 to 1.0 |
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| float | r | - |
| float | g | - |
| float | b | - |
| float | a | - |
## Static functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| Color | FromRGBA | (int r, int g, int b, int a) | int values from 0 to 255 |
| Color | FromHSB | (float flHue, float flSaturation, float flBrightness, float flAlpha) | - |
| float | GetHue | (Color color) | - |
# EspBounds
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| Vector2D | vecTopLeft | - |
| Vector2D | vecTopRight | - |
| Vector2D | vecLeftTop | - |
| Vector2D | vecLeftBottom | - |
| Vector2D | vecRightTop | - |
| Vector2D | vecRightBottom | - |
| Vector2D | vecBottomLeft | - |
| Vector2D | vecBottomRight | - |
# QAngle
## Constructors
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| QAngle | new | (float x, float y, float z) | - |
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| float | x | pitch |
| float | y | yaw |
| float | z | roll |
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | IsEqual | (QAngle angCompare) | - |
| bool | IsZero | () | - |
| float | Length | () | - |
| float | Length2D | () | - |
| float | DistTo | (Vector vecTo) | - |
| QAngle | Normalized | () | - |
| QAngle | MathNormalized | () | like Vector:Normalized() |
| QAngle | Clamp | () | clamp themself and return themself |
# Vector
## Constructors
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| Vector | new | (float x, float y, float z) | - |
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| float | x | - |
| float | y | - |
| float | z | - |
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | IsEqual | (Vector vecCompare) | - |
| bool | IsZero | () | - |
| float | Length | () | - |
| float | Length2D | () | - |
| float | DistTo | (Vector vecTo) | - |
| Vector | Normalized | () | - |
| float | DotProduct | (Vector vecDot) | - |
| Vector | DotProduct | (Vector vecCross) | - |
# Vector2D
## Constructors
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| Vector2D | new | (float x, float y) | - |
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| float | x | - |
| float | y | - |
# Esp
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | AddText | (void* pFont, float flFontSize, EspBounds* pBounds, string szText, Color color, EDrawPosition pos, ETextFlags flags) | - |
| void | AddEspText | (void* pFont, float flFontSize, EspBounds* pBounds, string szText, Color color, EDrawPosition pos) | inherit esp render type |
| void | AddBar | (EspBounds* pBounds, float flValue, float flMaxValue, Color color, EDrawPosition pos, bool bFixedSize, Vector2D vecSize) | if bFixedSize is true then bar will use vecSize |
# Hooks
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | RegisterCallback | (string szEvent, function fnCallback) | register your callback to be called on a hack event |
| void | UnregisterCallback | (string szEvent) | unregister all your callbacks from this event |
## Events
| Name | Args | Description |
| :--- | :--- | :--- |
| OnDraw | - | - |
| OnCreateMove | (CUserCmd* pCmd) | - |
| OnPredictionEnd | (CUserCmd* pCmd) | - |
| OnCreateMoveEnd | (CUserCmd* pCmd) | - |
| OnPlayerEsp | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnPlayerEspEnd | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnBombEsp | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnBombEspEnd | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnWeaponEsp | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnWeaponEspEnd | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnGrenadeEsp | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnGrenadeEspEnd | (CBaseEntity* pEntity, EspBounds* pBounds) | - |
| OnGameEvent | (IGameEvent* pEvent) | hack event listener |
| OnFireEvent | (IGameEvent* pEvent) | default csgo event listener |
| OnOverrideView | - | - |
| OnDoPostScreenEffects | - | - |
# Log
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | Info | (string szText) | - |
| void | Debug | (string szText) | - |
| void | Error | (string szText) | - |
| void | Warn | (string szText) | - |
# Menu
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CMenu* | CreateWindow | (string szLabel, int nColumns) | columns must contains elements |
| bool | IsOpened | () | - |
## IMenuItem
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CCheckbox* | AddCheckbox | (string szLabel, bool bStartValue, function fnCallback) | callback is called when the value changes |
| CSliderFloat* | AddSliderFloat | (string szLabel, float flStartValue, float flMin, float flMax, function fnCallback, ESliderFlags flags) | - |
| CSliderInt* | AddSliderInt | (string szLabel, float flStartValue, float flMin, float flMax, function fnCallback, ESliderFlags flags) | - |
| CColorEdit* | AddColorEdit | (string szLabel, Color colStartValue, function fnCallback, EColorEditFlags) | - |
## IControlItem\<elementType> : IMenuItem
#### CCheckbox is IControlItem\<bool>, CSliderFloat is IControlItem\<float>, etc...
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| elementType | GetValue | () | - |
| void | SetValue | (elementType newValue) | - |
| void | SetTooltip | (string szTooltip) | tooltip which appears when you hover on element |
## CMenu : IMenuItem
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | NextColumn | () | - |
# Netvars
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| int | GetOffset | (string szPropName) | propname format: CBasePlayer->m_vecVelocity[0] |
# Packet
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | GetSendPacket | () | - |
| void | SetSendPacket | (bool bNew) | - |
| bool | GetAngleSync | () | - |
| void | SetAngleSync | (bool bNew) | if true then angle from CUserCmd in current CreateMove will be applied to local |
# Prediction
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| int | GetFlags | () | - |
| Vector | GetAbsOrigin | () | - |
| int | GetMoveType | () | - |
| Vector | GetOrigin | () | - |
| Vector | GetVelocity | () | - |
# Render
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void* | GetMainFont | () | - |
| void* | GetMainMediumFont | () | - |
| void* | GetIconsFont | () | - |
| Vector2D | CalcTextSize | (void* pFont, float flSize, string szText) | - |
| bool | WorldToScreen | (Vector vecPosition, OUT Vector2D& vecScreen) | - |
| void | EspBox | (Vector2D vecMin, Vector2D vecMax, Color color, float flEdgeFactor, bool bOutline) | - |
| void | Line | (Vector2D vecStart, Vector2D vecEnd, Color color, float flThickness) | - |
| void | Rect | (Vector2D vecMin, Vector2D vecMax, Color color, float flRounding, float flThickness, ERectFlags flags, ERoundCorners cornerFlags) | - |
| void | RectMultiColor | (Vector2D vecMin, Vector2D vecMax, Color colUpperLeft, Color colUpperRight, Color colBottomRight, Color colBottomLeft) | - |
| void | Polygon | (Vector2D vecPoints[], Color color, EPolygonFlags flags, bool bClosed, float flThickness) | if bClosed is false you can use this as PolyLine |
| void | Circle | (Vector2D vecCenter, float flRadius, Color color, int nSegments, ECircleFlags flags, float flThickness) | - |
| void | Text | (void* pFont, float flFontSize, Vector2D vecPosition, string szText, Color color, ETextFlags flags, Color colorOutline) | - |
# Utils
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | SetClantag | (string szTag) | - |
| float | RandomFloat | (float flMinValue, float flMaxValue) | - |
| int | RandomInt | (float iMinValue, float iMaxValue) | - |
| void | ChatHackPrint | (string szText) | print with kamidere in begin |
| void | ChatPrint | (string szText) | - |
| void | GetSoundLength | (string szPath) | return sound length for voice |
| void | PlaySoundToVoice | (string szPath, bool bLoopback) | - |
# ClientState
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| float | flNextCmdTime | - |
| float | flFrameTime | - |
| int | iLastOutgoingCommand | - |
| int | nChokedCommands | - |
| int | iLastCommandAck | - |
| int | iCommandAck | - |
| int | iCurrentSequence | - |
# CVar
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CConVar* | FindVar | (string szName) | - |
# Engine
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| Vector2D | GetScreenSize | () | - |
| PlayerInfo | GetPlayerInfo | (int nEntityIndex) | - |
| int | GetPlayerForUserID | (int nUserID) | - |
| bool | IsConsoleVisible | () | - |
| int | GetLocalPlayer | () | - |
| float | GetLastTimeStamp | () | - |
| QAngle | GetViewAngles | () | - |
| void | SetViewAngles | (QAngle angView) | - |
| int | GetMaxClients | () | - |
| INetChannelInfo* | GetNetChannelInfo | () | - |
| bool | IsInGame | () | - |
| bool | IsConnected | () | - |
| string | GetLevelName | () | - |
| string | GetLevelNameShort | () | - |
| bool | IsPlayingDemo | () | - |
| bool | IsRecordingDemo | () | - |
| bool | IsPlayingTimeDemo | () | - |
| bool | IsTakingScreenshot | () | - |
| bool | IsHLTV | () | - |
| int | GetEngineBuildNumber | () | - |
| void | ExecuteClientCmd | (string szCmdString) | - |
| int | ClientCmdUnrestricted | (string szCmdString, bool bFromConsoleOrKeybind) | - |
| bool | IsVoiceRecording | () | - |
# EntityList
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CBaseEntity* | GetEntityByIndex | (int iIndex) | - |
| CBaseEntity* | GetEntityByUserId | (int iUserId) | - |
| CBaseEntity* | GetEntityFromHandle | (void* handle) | - |
| int | GetHighestEntityIndex | () | - |
| int | GetMaxEntities | () | - |
# EventListener
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | AddEvent | (string szEvent) | adds event to hack event listener (OnGameEvent), this may affect to detection on community servers with server-side anti-cheats |
# GlobalVars
## Fields
| Type | Name | Description |
| :--- | :--- | :--- |
| float | flRealTime | - |
| int | iFrameCount | - |
| float | flAbsFrameTime | - |
| float | flAbsFrameStartTime | - |
| float | flCurrentTime | - |
| float | flFrameTime | - |
| int | nMaxClients | - |
| int | iTickCount | - |
| float | flIntervalPerTick | - |
| float | flInterpolationAmount | - |
| int | nFrameSimulationTicks | - |
| int | iNetworkProtocol | - |
| void | pSaveData | - |
| bool | bClient | - |
| bool | bRemoteClient | - |
| int | iTimestampNetworkingBase | - |
| int | iTimestampRandomizeWindow | - |
# Panorama
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void* | GetHudPanel | () | - |
| int | RunScript | (void* pPanelContext, string szJsCode) | - |
# Surface
## Functions
| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | PlaySound | (string szPath) | - |
