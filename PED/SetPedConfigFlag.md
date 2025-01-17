---
ns: PED
---
## SET_PED_CONFIG_FLAG

```c
// 0x1913FE4CBF41C463 0x9CFBE10D
void SET_PED_CONFIG_FLAG(Ped ped, int flagId, BOOL value);
```

```c
// Potential names and hash collisions included as comments
enum ePedConfigFlags {
	_0x67D1A445 = 0,
	_0xC63DE95E = 1,
	CPED_CONFIG_FLAG_NoCriticalHits = 2,
	CPED_CONFIG_FLAG_DrownsInWater = 3,
	CPED_CONFIG_FLAG_DisableReticuleFixedLockon = 4,
	_0x37D196F4 = 5,
	_0xE2462399 = 6,
	CPED_CONFIG_FLAG_UpperBodyDamageAnimsOnly = 7,
	_0xEDDEB838 = 8,
	_0xB398B6FD = 9,
	_0xF6664E68 = 10,
	_0xA05E7CA3 = 11,
	_0xCE394045 = 12,
	CPED_CONFIG_FLAG_NeverLeavesGroup = 13,
	_0xCD8D1411 = 14,
	_0xB031F1A9 = 15,
	_0xFE65BEE3 = 16,
	CPED_CONFIG_FLAG_BlockNonTemporaryEvents = 17,
	_0x380165BD = 18,
	_0x07C045C7 = 19,
	_0x583B5E2D = 20,
	_0x475EDA58 = 21,
	_0x8629D05B = 22,
	_0x1522968B = 23,
	CPED_CONFIG_FLAG_IgnoreSeenMelee = 24,
	_0x4CC09C4B = 25,
	_0x034F3053 = 26,
	_0xD91BA7CC = 27,
	_0x5C8DC66E = 28,
	_0x8902EAA0 = 29,
	_0x6580B9D2 = 30,
	_0x0EF7A297 = 31,
	_0x6BF86E5B = 32,
	CPED_CONFIG_FLAG_DieWhenRagdoll = 33,
	CPED_CONFIG_FLAG_HasHelmet = 34,
	CPED_CONFIG_FLAG_UseHelmet = 35,
	_0xEEB3D630 = 36,
	_0xB130D17B = 37,
	_0x5F071200 = 38,
	CPED_CONFIG_FLAG_DisableEvasiveDives = 39,
	_0xC287AAFF = 40,
	_0x203328CC = 41,
	CPED_CONFIG_FLAG_DontInfluenceWantedLevel = 42,
	CPED_CONFIG_FLAG_DisablePlayerLockon = 43,
	CPED_CONFIG_FLAG_DisableLockonToRandomPeds = 44,
	_0xEC4A8ACF = 45,
	_0xDB115BFA = 46,
	CPED_CONFIG_FLAG_PedBeingDeleted = 47,
	CPED_CONFIG_FLAG_BlockWeaponSwitching = 48,
	_0xF8E99565 = 49,
	_0xDD17FEE6 = 50,
	_0x7ED9B2C9 = 51,
	_0x655E8618 = 52,
	_0x5A6C1F6E = 53,
	_0xD749FC41 = 54,
	_0x357F63F3 = 55,
	_0xC5E60961 = 56,
	_0x29275C3E = 57,
	CPED_CONFIG_FLAG_IsFiring = 58,
	CPED_CONFIG_FLAG_WasFiring = 59,
	CPED_CONFIG_FLAG_IsStanding = 60,
	CPED_CONFIG_FLAG_WasStanding = 61,
	CPED_CONFIG_FLAG_InVehicle = 62,
	CPED_CONFIG_FLAG_OnMount = 63,
	CPED_CONFIG_FLAG_AttachedToVehicle = 64,
	CPED_CONFIG_FLAG_IsSwimming = 65,
	CPED_CONFIG_FLAG_WasSwimming = 66,
	CPED_CONFIG_FLAG_IsSkiing = 67,
	CPED_CONFIG_FLAG_IsSitting = 68,
	CPED_CONFIG_FLAG_KilledByStealth = 69,
	CPED_CONFIG_FLAG_KilledByTakedown = 70,
	CPED_CONFIG_FLAG_Knockedout = 71,
	_0x3E3C4560 = 72,
	_0x2994C7B7 = 73,
	_0x6D59D275 = 74,
	CPED_CONFIG_FLAG_UsingCoverPoint = 75,
	CPED_CONFIG_FLAG_IsInTheAir = 76,
	_0x2D493FB7 = 77,
	CPED_CONFIG_FLAG_IsAimingGun = 78,
	_0x14D69875 = 79,
	_0x40B05311 = 80,
	_0x8B230BC5 = 81,
	_0xC74E5842 = 82,
	_0x9EA86147 = 83,
	_0x674C746C = 84,
	_0x3E56A8C2 = 85,
	_0xC144A1EF = 86,
	_0x0548512D = 87,
	_0x31C93909 = 88,
	_0xA0269315 = 89,
	_0xD4D59D4D = 90,
	_0x411D4420 = 91,
	_0xDF4AEF0D = 92,
	CPED_CONFIG_FLAG_ForcePedLoadCover = 93,
	_0x300E4CD3 = 94,
	_0xF1C5BF04 = 95,
	_0x89C2EF13 = 96,
	CPED_CONFIG_FLAG_VaultFromCover = 97,
	_0x02A852C8 = 98,
	_0x3D9407F1 = 99,
	_0x319B4558 = 100,
	CPED_CONFIG_FLAG_ForcedAim = 101,
	_0xB942D71A = 102,
	_0xD26C55A8 = 103,
	_0xB89E703B = 104,
	CPED_CONFIG_FLAG_ForceReload = 105,
	_0xD9E73DA2 = 106,
	_0xFF71DC2C = 107,
	_0x1E27E8D8 = 108,
	_0xF2C53966 = 109,
	_0xC4DBE247 = 110,
	_0x83C0A4BF = 111,
	_0x0E0FAF8C = 112,
	_0x26616660 = 113,
	_0x43B80B79 = 114,
	_0x0D2A9309 = 115,
	_0x12C1C983 = 116,
	CPED_CONFIG_FLAG_BumpedByPlayer = 117,
	_0xE586D504 = 118,
	_0x52374204 = 119,
	CPED_CONFIG_FLAG_IsHandCuffed = 120,
	CPED_CONFIG_FLAG_IsAnkleCuffed = 121,
	CPED_CONFIG_FLAG_DisableMelee = 122,
	_0xFE714397 = 123,
	_0xB3E660BD = 124,
	_0x5FED6BFD = 125,
	_0xC9D6F66F = 126,
	_0x519BC986 = 127,
	CPED_CONFIG_FLAG_CanBeAgitated = 128,
	_0x9A4B617C = 129, // CPED_CONFIG_FLAG_FaceDirInsult
	_0xDAB70E9F = 130,
	_0xE569438A = 131,
	_0xBBC77D6D = 132,
	_0xCB59EF0F = 133,
	_0x8C5EA971 = 134,
	CPED_CONFIG_FLAG_IsScuba = 135,
	CPED_CONFIG_FLAG_WillArrestRatherThanJack = 136,
	_0xDCE59B58 = 137,
	CPED_CONFIG_FLAG_RidingTrain = 138,
	CPED_CONFIG_FLAG_ArrestResult = 139,
	CPED_CONFIG_FLAG_CanAttackFriendly = 140,
	_0x98A4BE43 = 141,
	_0x6901E731 = 142,
	_0x9EC9BF6C = 143,
	_0x42841A8F = 144,
	CPED_CONFIG_FLAG_ShootingAnimFlag = 145,
	CPED_CONFIG_FLAG_DisableLadderClimbing = 146,
	CPED_CONFIG_FLAG_StairsDetected = 147,
	CPED_CONFIG_FLAG_SlopeDetected = 148,
	_0x1A15670B = 149,
	_0x61786EE5 = 150,
	_0xCB9186BD = 151,
	_0xF0710152 = 152,
	_0x43DFE310 = 153,
	_0xC43C624E = 154,
	CPED_CONFIG_FLAG_CanPerformArrest = 155,
	CPED_CONFIG_FLAG_CanPerformUncuff = 156,
	CPED_CONFIG_FLAG_CanBeArrested = 157,
	_0xF7960FF5 = 158,
	_0x59564113 = 159,
	_0x0C6C3099 = 160,
	_0x645F927A = 161,
	_0xA86549B9 = 162,
	_0x8AAF337A = 163,
	_0x13BAA6E7 = 164,
	_0x5FB9D1F5 = 165,
	CPED_CONFIG_FLAG_IsInjured = 166,
	_0x6398A20B = 167,
	_0xD8072639 = 168,
	_0xA05B1845 = 169,
	_0x83F6D220 = 170,
	_0xD8430331 = 171,
	_0x4B547520 = 172,
	_0xE66E1406 = 173,
	_0x1C4BFE0C = 174,
	_0x90008BFA = 175,
	_0x07C7A910 = 176,
	_0xF15F8191 = 177,
	_0xCE4E8BE2 = 178,
	_0x1D46E4F2 = 179,
	CPED_CONFIG_FLAG_IsInCustody = 180,
	_0xE4FD9B3A = 181,
	_0x67AE0812 = 182,
	CPED_CONFIG_FLAG_IsAgitated = 183,
	CPED_CONFIG_FLAG_PreventAutoShuffleToDriversSeat = 184,
	_0x7B2D325E = 185,
	CPED_CONFIG_FLAG_EnableWeaponBlocking = 186,
	CPED_CONFIG_FLAG_HasHurtStarted = 187,
	CPED_CONFIG_FLAG_DisableHurt = 188,
	CPED_CONFIG_FLAG_PlayerIsWeird = 189,
	_0x32FC208B = 190,
	_0x0C296E5A = 191,
	_0xE63B73EC = 192,
	_0x04E9CC80 = 193,
	CPED_CONFIG_FLAG_UsingScenario = 194,
	CPED_CONFIG_FLAG_VisibleOnScreen = 195,
	_0xD88C58A1 = 196,
	_0x5A3DCF43 = 197, // CPED_CONFIG_FLAG_AvoidUnderSide
	_0xEA02B420 = 198,
	_0x3F559CFF = 199,
	_0x8C55D029 = 200,
	_0x5E6466F6 = 201,
	_0xEB5AD706 = 202,
	_0x0EDDDDE7 = 203,
	_0xA64F7B1D = 204,
	_0x48532CBA = 205,
	_0xAA25A9E7 = 206,
	_0x415B26B9 = 207,
	CPED_CONFIG_FLAG_DisableExplosionReactions = 208,
	CPED_CONFIG_FLAG_DodgedPlayer = 209,
	_0x67405504 = 210,
	_0x75DDD68C = 211,
	_0x2AD879B4 = 212,
	_0x51486F91 = 213,
	_0x32F79E21 = 214,
	_0xBF099213 = 215,
	_0x054AC8E2 = 216,
	_0x14E495CC = 217,
	_0x3C7DF9DF = 218,
	_0x848FFEF2 = 219,
	CPED_CONFIG_FLAG_DontEnterLeadersVehicle = 220,
	_0x2618E1CF = 221,
	_0x84F722FA = 222,
	_0xD1B87B1F = 223,
	_0x728AA918 = 224,
	CPED_CONFIG_FLAG_DisablePotentialToBeWalkedIntoResponse = 225,
	CPED_CONFIG_FLAG_DisablePedAvoidance = 226,
	_0x59E91185 = 227,
	_0x1EA7225F = 228,
	CPED_CONFIG_FLAG_DisablePanicInVehicle = 229,
	_0x6DCA7D88 = 230,
	_0xFC3E572D = 231,
	_0x08E9F9CF = 232,
	_0x2D3BA52D = 233,
	_0xFD2F53EA = 234,
	_0x31A1B03B = 235,
	CPED_CONFIG_FLAG_IsHoldingProp = 236,
	_0x82ED0A66 = 237, // CPED_CONFIG_FLAG_BlocksPathingWhenDead
	_0xCE57C9A3 = 238,
	_0x26149198 = 239,
	_0x1B33B598 = 240,
	_0x719B6E87 = 241,
	_0x13E8E8E8 = 242,
	_0xF29739AE = 243,
	_0xABEA8A74 = 244,
	_0xB60EA2BA = 245,
	_0x536B0950 = 246,
	_0x0C754ACA = 247,
	CPED_CONFIG_FLAG_DisableVehicleSeatRandomAnimations = 248,
	_0x12659168 = 249,
	_0x1BDF2F04 = 250,
	_0x7728FAA3 = 251,
	_0x6A807ED8 = 252,
	CPED_CONFIG_FLAG_OnStairs = 253,
	_0xE1A2F73F = 254,
	_0x5B3697C8 = 255,
	_0xF1EB20A9 = 256,
	_0x8B7DF407 = 257,
	_0x329DCF1A = 258,
	_0x8D90DD1B = 259,
	_0xB8A292B7 = 260,
	_0x8374B087 = 261,
	_0x2AF558F0 = 262,
	_0x82251455 = 263,
	_0x30CF498B = 264,
	_0xE1CD50AF = 265,
	_0x72E4AE48 = 266,
	_0xC2657EA1 = 267,
	_0x29FF6030 = 268,
	_0x8248A5EC = 269,
	CPED_CONFIG_FLAG_OnStairSlope = 270,
	_0xA0897933 = 271,
	CPED_CONFIG_FLAG_DontBlipCop = 272,
	CPED_CONFIG_FLAG_ClimbedShiftedFence = 273,
	_0xF7823618 = 274,
	_0xDC305CCE = 275, // CPED_CONFIG_FLAG_KillWhenTrapped
	CPED_CONFIG_FLAG_EdgeDetected = 276,
	_0x92B67896 = 277,
	_0xCAD677C9 = 278,
	CPED_CONFIG_FLAG_AvoidTearGas = 279,
	_0x5276AC7B = 280,
	_0x1032692A = 281,
	_0xDA23E7F1 = 282,
	_0x9139724D = 283,
	_0xA1457461 = 284,
	_0x4186E095 = 285,
	_0xAC68E2EB = 286,
	CPED_CONFIG_FLAG_RagdollingOnBoat = 287,
	CPED_CONFIG_FLAG_HasBrandishedWeapon = 288,
	_0x1B9EE8A1 = 289,
	_0xF3F5758C = 290,
	_0x2A9307F1 = 291,
	_0x7403D216 = 292,
	_0xA06A3C6C = 293,
	CPED_CONFIG_FLAG_DisableShockingEvents = 294,
	_0xF8DA25A5 = 295,
	_0x7EF55802 = 296,
	_0xB31F1187 = 297,
	_0x84315402 = 298,
	_0x0FD69867 = 299,
	_0xC7829B67 = 300,
	CPED_CONFIG_FLAG_DisablePedConstraints = 301,
	_0x6D23CF25 = 302,
	_0x2ADA871B = 303,
	_0x47BC8A58 = 304,
	_0xEB692FA5 = 305,
	_0x4A133C50 = 306,
	_0xC58099C3 = 307,
	_0xF3D76D41 = 308,
	_0xB0EEE9F2 = 309,
	CPED_CONFIG_FLAG_IsInCluster = 310,
	_0x0FA153EF = 311,
	_0xD73F5CD3 = 312,
	_0xD4136C22 = 313,
	_0xE404CA6B = 314,
	_0xB9597446 = 315,
	_0xD5C98277 = 316,
	_0xD5060A9C = 317,
	_0x3E5F1CBB = 318,
	_0xD8BE1D54 = 319,
	_0x0B1F191F = 320,
	_0xC995167A = 321,
	CPED_CONFIG_FLAG_HasHighHeels = 322,
	_0x86B01E54 = 323,
	_0x3A56FE15 = 324,
	_0xC03B736C = 325, // CPED_CONFIG_FLAG_SpawnedAtScenario
	_0xBBF47729 = 326,
	_0x22B668A8 = 327,
	_0x2624D4D4 = 328,
	CPED_CONFIG_FLAG_DisableTalkTo = 329,
	CPED_CONFIG_FLAG_DontBlip = 330,
	CPED_CONFIG_FLAG_IsSwitchingWeapon = 331,
	_0x630F55F3 = 332,
	_0x150468FD = 333,
	_0x914EBD6B = 334,
	_0x79AF3B6D = 335,
	_0x75C7A632 = 336,
	_0x52D530E2 = 337,
	_0xDB2A90E0 = 338,
	_0x5922763D = 339,
	_0x12ADB567 = 340,
	_0x105C8518 = 341,
	_0x106F703D = 342,
	_0xED152C3E = 343,
	_0xA0EFE6A8 = 344,
	_0xBF348C82 = 345,
	_0xCDDFE830 = 346,
	_0x7B59BD9B = 347,
	_0x0124C788 = 348,
	CPED_CONFIG_FLAG_EquipJetpack = 349,
	_0x08D361A5 = 350,
	_0xE13D1F7C = 351,
	_0x40E25FB9 = 352,
	_0x930629D9 = 353,
	_0xECCF0C7F = 354,
	_0xB6E9613B = 355,
	_0x490C0478 = 356,
	_0xE8865BEA = 357,
	_0xF3C34A29 = 358,
	CPED_CONFIG_FLAG_IsDuckingInVehicle = 359,
	_0xF660E115 = 360,
	_0xAB0E6DED = 361,
	CPED_CONFIG_FLAG_HasReserveParachute = 362,
	CPED_CONFIG_FLAG_UseReserveParachute = 363,
	_0x5C5D9CD3 = 364,
	_0x8F7701F3 = 365,
	_0xBC4436AD = 366,
	_0xD7E07D37 = 367,
	_0x03C4FD24 = 368,
	_0x7675789A = 369,
	_0xB7288A88 = 370,
	_0xC06B6291 = 371,
	_0x95A4A805 = 372,
	_0xA8E9A042 = 373,
	CPED_CONFIG_FLAG_NeverLeaveTrain = 374,
	_0xBAC674B3 = 375,
	_0x147F1FFB = 376,
	_0x4376DD79 = 377,
	_0xCD3DB518 = 378,
	_0xFE4BA4B6 = 379,
	_0x5DF03A55 = 380,
	_0xBCD816CD = 381,
	_0xCF02DD69 = 382,
	_0xF73AFA2E = 383,
	_0x80B9A9D0 = 384,
	_0xF601F7EE = 385,
	_0xA91350FC = 386,
	_0x3AB23B96 = 387,
	CPED_CONFIG_FLAG_IsClimbingLadder = 388,
	CPED_CONFIG_FLAG_HasBareFeet = 389,
	_0xB4B1CD4C = 390,
	_0x5459AFB8 = 391,
	_0x54F27667 = 392,
	_0xC11D3E8F = 393,
	_0x5419EB3E = 394,
	_0x82D8DBB4 = 395,
	_0x33B02D2F = 396,
	_0xAE66176D = 397,
	_0xA2692593 = 398,
	_0x714C7E31 = 399,
	_0xEC488AC7 = 400,
	_0xAE398504 = 401,
	_0xABC58D72 = 402,
	_0x5E5B9591 = 403,
	_0x6BA1091E = 404,
	_0x77840177 = 405,
	_0x1C7ACAC4 = 406,
	_0x124420E9 = 407,
	_0x75A65587 = 408,
	_0xDFD2D55B = 409,
	_0xBDD39919 = 410,
	_0x43DEC267 = 411,
	_0xE42B7797 = 412,
	CPED_CONFIG_FLAG_IsHolsteringWeapon = 413,
	_0x4F8149F5 = 414,
	_0xDD9ECA7A = 415,
	_0x9E7EF9D2 = 416,
	_0x2C6ED942 = 417,
	CPED_CONFIG_FLAG_IsSwitchingHelmetVisor = 418,
	_0xA488727D = 419,
	_0xCFF5F6DE = 420,
	_0x6D614599 = 421,
	CPED_CONFIG_FLAG_DisableVehicleCombat = 422,
	_0xFE401D26 = 423,
	CPED_CONFIG_FLAG_FallsLikeAircraft = 424, // Will put ped into a "relaxed" riding position on motorcycles and certain cars at low speeds.
	_0x2B42AE82 = 425,
	_0x7A95734F = 426,
	_0xDF4D8617 = 427,
	_0x578F1F14 = 428,
	CPED_CONFIG_FLAG_DisableStartEngine = 429,
	CPED_CONFIG_FLAG_IgnoreBeingOnFire = 430,
	_0x153C9500 = 431,
	_0xCB7A632E = 432,
	_0xDE727981 = 433,
	CPED_CONFIG_FLAG_DisableHomingMissileLockon = 434,
	_0x12BBB935 = 435,
	_0xAD0A1277 = 436,
	_0xEA6AA46A = 437,
	CPED_CONFIG_FLAG_DisableHelmetArmor = 438,
	_0xCB7F3A1E = 439,
	_0x50178878 = 440,
	_0x051B4F0D = 441,
	_0x2FC3DECC = 442,
	_0xC0030B0B = 443,
	_0xBBDAF1E9 = 444,
	_0x944FE59C = 445,
	_0x506FBA39 = 446,
	_0xDD45FE84 = 447,
	_0xE698AE75 = 448,
	_0x199633F8 = 449,
	CPED_CONFIG_FLAG_PedIsArresting = 450,
	CPED_CONFIG_FLAG_IsDecoyPed = 451,
	_0x3A251D83 = 452,
	_0xA56F6986 = 453,
	_0x1D19C622 = 454,
	_0xB68D3EAB = 455,
	CPED_CONFIG_FLAG_CanBeIncapacitated = 456,
	_0x4BD5EBAD = 457,
}
```

## Parameters
* **ped**: 
* **flagId**: 
* **value**: 

