# Option Codes

The `option_codes` field of a vehicle is a comma-delimited set of codes that
represent various options the car was built with. This can include trim options,
battery sizes, color, wheel types, and addon packages.

_This list needs a lot of help! If you know of what any of these mean, please
edit this page and submit a_
[_pull request_](https://github.com/timdorr/tesla-api/pulls)_. It is much
appreciated!_

**As of August 2019, Option Codes cannot be relied on.** Vehicles now
return a generic set of codes related to a Model 3.

| Code   | Title                                                    | Description                                               |
| :----- | :------------------------------------------------------- | :-------------------------------------------------------- |
| MDLS   | Model S                                                  | This vehicle is a Model S                                 |
| MS03   | Model S                                                  | This vehicle is a Model S                                 |
| MS04   | Model S                                                  | This vehicle is a Model S                                 |
| MDLX   | Model X                                                  | This vehicle is a Model X                                 |
| MDL3   | Model 3                                                  | This vehicle is a Model 3                                 |
| MDLY   | Model Y                                                  | This vehicle is a Model Y                                 |
| RENA   | Region: North America                                    |                                                           |
| RENC   | Region: Canada                                           |                                                           |
| REEU   | Region: Europe                                           |                                                           |
| ACL1   | Ludicrous Mode                                           | Model X                                                   |
| AD02   | NEMA 14-50                                               |                                                           |
| AD04   | European 3-Phase                                         |                                                           |
| AD05   | European 3-Phase, IT                                     |                                                           |
| AD06   | Schuko (1 phase, 230V 13A)                               |                                                           |
| AD07   | Red IEC309 (3 phase, 400V 16A)                           |                                                           |
| AD08   | Blue Charging Adapter                                    |                                                           |
| AD09   | Adapter, Swiss (1 phase, 10A)                            |                                                           |
| AD10   | Adapter, Denmark (1 phase, 13A)                          |                                                           |
| AD11   | Adapter, Italy (1 phase, 13A)                            |                                                           |
| AD15   | Adapter                                                  | J1772                                                     |
| ADPX2  | Type 2 Public Charging Connector                         |                                                           |
| ADX4   | No European 3-Phase                                      |                                                           |
| ADX5   | European 3-Phase, IT                                     |                                                           |
| ADX6   | No - Adapter, Schuko (1 phase, 13A)                      |                                                           |
| ADX7   | No - 3-ph Red IEC309 (3 phase, 16A)                      |                                                           |
| ADX9   | No - Adapter, Swiss (1 phase, 10A)                       |                                                           |
| ADX8   | Blue IEC309 (1 phase, 230V 32A)                          |                                                           |
| AF00   | No HEPA Filter                                           | Standard air filter, no air ionizer                       |
| AF02   | HEPA Filter                                              |                                                           |
| AH00   | No Accessory Hitch                                       |                                                           |
| APB1   | Autopilot with convenience features                      | Model S                                                   |
| APBS   | Autopilot                                                | Model 3 Autopilot                                         |
| APF0   | Autopilot Firmware 2.0 Base                              |                                                           |
| APF1   | Autopilot Firmware 2.0 Enhanced                          |                                                           |
| APFB   | Full Self-Driving Hardware                               | Car has FSD hardware, but sofware option is not purchased |
| APF2   | Full Self-Driving Hardware (Activated)                   | Car has active FSD software purchase                      |
| APPB   | Enhanced Autopilot                                       | Navigate on Autopilot, Auto Lane Change, Autopark, Summon |
| APH1   | Hardware 1.0                                             |                                                           |
| APH2   | Hardware 2.0                                             |                                                           |
| APH3   | Hardware 2.5                                             |                                                           |
| APPF   | Full Self-Driving Capability                             |                                                           |
| APH4   | Hardware 3.0                                             |                                                           |
| AU00   | No Audio Package                                         |                                                           |
| AU01   | Ultra High Fidelity Sound                                |                                                           |
| AU3P   | Sound Studio Package                                     | Premium audio package                                     |
| BC0B   | Black Brake Calipers                                     |                                                           |
| BC0R   | Red Brake Calipers                                       |                                                           |
| BC3B   | Black Brake Calipers, Model 3                            |                                                           |
| BCMB   | Black Brake Calipers, Mando Brakes                       |                                                           |
| BCYR   | Performance Brakes                                       |                                                           |
| BG30   | No Badge                                                 | Model 3                                                   |
| BG31   | AWD Badge                                                | Model 3                                                   |
| BG32   | Performance AWD Badge                                    | Model 3                                                   |
| BP00   | No Ludicrous                                             |                                                           |
| BP01   | Ludicrous Speed Upgrade                                  |                                                           |
| BP02   | Uncorked Acceleration                                    | Non-Performance                                           |
| BR00   | No Battery Firmware Limit                                |                                                           |
| BR03   | Battery Firmware Limit (60kWh)                           |                                                           |
| BR05   | Battery Firmware Limit (75kWh)                           |                                                           |
| BS00   | Blind Spot Sensor Package                                |                                                           |
| BS01   | Special Production Flag                                  |                                                           |
| BT37   | 75 kWh (Model 3)                                         |                                                           |
| BT40   | 40 kWh                                                   |                                                           |
| BT60   | 60 kWh                                                   |                                                           |
| BT70   | 70 kWh                                                   |                                                           |
| BT85   | 85 kWh                                                   |                                                           |
| BTX4   | 90 kWh                                                   |                                                           |
| BTX5   | 75 kWh                                                   |                                                           |
| BTX6   | 100 kWh                                                  |                                                           |
| BTX7   | 75 kWh                                                   |                                                           |
| BTX8   | 75 kWh                                                   |                                                           |
| CC01   | Five Seat Interior                                       |                                                           |
| CC02   | Six Seat Interior                                        |                                                           |
| CC03   | Seven Seat Interior                                      |                                                           |
| CC04   | Seven Seat Interior                                      |                                                           |
| CC12   | Six Seat Interior with Center Console                    |                                                           |
| CDM0   | No CHAdeMO Charging Adaptor                              |                                                           |
| CF00   | High Power Charger                                       |                                                           |
| CF01   | 48amp charger                                            |                                                           |
| CH00   | Standard Charger (40 Amp)                                |                                                           |
| CH01   | Dual Chargers (80 Amp)                                   | Twin 10kW charge config                                   |
| CH04   | 72 Amp Charger (Model S/X)                               |                                                           |
| CH05   | 48 Amp Charger (Model S/X)                               |                                                           |
| CH07   | 48 Amp Charger (Model 3)                                 |                                                           |
| COL0   | Signature                                                |                                                           |
| COL1   | Solid                                                    |                                                           |
| COL2   | Metallic                                                 |                                                           |
| COL3   | Tesla Multi-Coat                                         |                                                           |
| COBE   | Country: Belgium                                         |                                                           |
| CODE   | Country: Germany                                         |                                                           |
| COES   | Country: Spain                                           |                                                           |
| COFR   | Country: France                                          |                                                           |
| CONL   | Country: Netherlands                                     |                                                           |
| COUS   | Country: United States                                   |                                                           |
| CPF0   | Standard Connectivity                                    |                                                           |
| CPF1   | Premium Connectivity                                     |                                                           |
| CPW1   | 20" Performance Wheels                                   |                                                           |
| CW00   | No Weather Package                                       | No Cold Weather Package                                   |
| CW02   | Weather Package                                          | Subzero Weather Package                                   |
| DA00   | No Autopilot                                             |                                                           |
| DA01   | Active Safety (ACC,LDW,SA)                               | Drivers Assistance Package                                |
| DA02   | Autopilot Convenience Features                           |                                                           |
| DCF0   | Autopilot Convenience Features                           |                                                           |
| DRLH   | Left Hand Drive                                          |                                                           |
| BC3R   | Performance Brakes                                       | Model 3                                                   |
| DRRH   | Right Hand Drive                                         |                                                           |
| DSH5   | Dashboard                                                | PUR Dashboard Pad                                         |
| DSH7   | Alcantara Dashboard Accents                              |                                                           |
| DSHG   | PUR Dash Pad                                             |                                                           |
| DU00   | Drive Unit - IR                                          |                                                           |
| DU01   | Drive Unit - Infineon                                    |                                                           |
| DV2W   | Rear-Wheel Drive                                         |                                                           |
| DV4W   | All-Wheel Drive                                          |                                                           |
| FC3P   | Front Console Front Console (Premium)                    | Model 3                                                   |
| FG00   | No Exterior Lighting Package                             |                                                           |
| FG01   | Fog Lamps                                                | Exterior Lighting Package                                 |
| FG02   | Fog Lamps                                                | Fog Lamps                                                 |
| FG31   | Fog Lamps                                                | Model Premium Fog Lights                                  |
| FM3B   | Performance Package                                      | Model 3                                                   |
| FM3U   | Acceleration Boost                                       | Model 3 Long Range All-Wheel Drive                        |
| FMP6   | Performance Firmware                                     |                                                           |
| FR01   | Base Front Row                                           |                                                           |
| FR02   | Ventilated Front Seats                                   |                                                           |
| FR03   | FR03                                                     |                                                           |
| FR04   | FR04                                                     |                                                           |
| GLFR   | Assembly                                                 | Final Assembly Fremont                                    |
| HC00   | No Home Charging installation                            |                                                           |
| HC01   | Home Charging Installation                               |                                                           |
| HM31   | Teck Package - Homelink                                  | Homelink                                                  |
| HL31   | Head Lamp                                                | Model 3 Uplevel Headlamps                                 |
| HP00   | No HPWC Ordered                                          |                                                           |
| HP01   | HPWC Ordered                                             |                                                           |
| IBB0   | All Black Interior                                       | Model 3 Interior (Left Hand Drive)                        |
| IBB1   | All Black Interior                                       | Model 3 Interior (Right Hand Drive)                       |
| ID3W   | Wood Decor                                               | Model 3                                                   |
| IDBA   | Dark Ash Wood Decor                                      |                                                           |
| IDBO   | Figured Ash Wood Decor                                   |                                                           |
| IDCF   | Carbon Fiber Decor                                       |                                                           |
| IDHM   | Matte Obeche Wood Decor                                  |                                                           |
| IDOK   | Oak Decor                                                |                                                           |
| IDOM   | Matte Obeche Wood Decor                                  |                                                           |
| IDOG   | Gloss Obeche Wood Decor                                  |                                                           |
| IDLW   | Lacewood Decor                                           |                                                           |
| IDPB   | Piano Black Decor                                        |                                                           |
| IN3BB  | All Black Partial Premium Interior                       |                                                           |
| IBW0   | Black and White Interior                                 | Model 3 Interior (Left Hand Drive)                        |
| IBW1   | Black and White Interior                                 | Model 3 Interior (Right Hand Drive)                       |
| IN3BW  | Black and White Interior                                 | Model 3 Interior                                          |
| IN3PB  | All Black Premium Interior                               | Model 3 Interior                                          |
| IN3PW  | All White Premium Interior                               | Model 3 Interior                                          |
| INBBW  | White Interior                                           |                                                           |
| INB3C  | Premium beige interior with oak wood finishes            | Model X                                                   |
| INBC3W | Premium black and white interior with Carbon Fiber decor | Model X                                                   |
| INBFP  | Classic Black Interior                                   |                                                           |
| INBPP  | Black Interior                                           |                                                           |
| INBPW  | White Seats Interior                                     |                                                           |
| INBTB  | Multi-Pattern Black Interior                             |                                                           |
| INFBP  | Black Premium Interior                                   |                                                           |
| INLPC  | Cream Interior                                           |                                                           |
| INLPP  | Black / Light Headliner Interior                         |                                                           |
| INWPT  | Tan Interior                                             |                                                           |
| INYPB  | All Black Premium Interior                               |                                                           |
| INYPW  | Black and White Premium Interior                         |                                                           |
| IL31   | Interior Ambient Lighting Interior                       |                                                           |
| IPB0   | Black Interior                                           | Model 3 Interior (Left Hand Drive)                        |
| IPB1   | Black Interior                                           | Model 3 Interior (Right Hand Drive)                       |
| IPW0   | White Interior                                           | Model 3 Interior (Left Hand Drive)                        |
| IPW1   | white Interior                                           | Model 3 Interior (Right Hand Drive)                       |
| IVBPP  | All Black Interior                                       |                                                           |
| IVBSW  | Ultra White Interior                                     |                                                           |
| IVBTB  | All Black Interior                                       |                                                           |
| IVLPC  | Vegan Cream Interior                                     |                                                           |
| IX00   | No Extended Nappa Leather Trim                           |                                                           |
| IX01   | Extended Nappa Leather Trim                              |                                                           |
| LLP1   | LLP1                                                     |                                                           |
| LLP2   | LLP2                                                     |                                                           |
| LP00   | Lighting Package                                         | No Lighting Package                                       |
| LP01   | Lighting Package                                         | Premium Interior Lighting                                 |
| LT00   | Vegan interior                                           |                                                           |
| LT01   | Standard interior                                        |                                                           |
| LT1B   | Lower Trim                                               | Lower Trim                                                |
| LT3W   | LT3W                                                     |                                                           |
| LT4B   | LT4B                                                     |                                                           |
| LT4C   | LT4C                                                     |                                                           |
| LT4W   | LT4W                                                     |                                                           |
| LT5C   | LT5C                                                     |                                                           |
| LT5P   | LT5P                                                     |                                                           |
| LT6P   | LT6P                                                     |                                                           |
| LT6W   | White Base Lower Trim                                    |                                                           |
| LTPB   | Lower Trim PUR Black                                     |                                                           |
| LTPW   | Lower Trim PUR White                                     |                                                           |
| ME01   | Memory Seats                                             |                                                           |
| ME02   | Seat Memory                                              | Seat Memory LHD Driver                                    |
| MI00   | 1st Generation Production                                | Model 3 (2019), Model S (Nosecone), Model X (2016)        |
| MI01   | 2nd Generation Production                                | Model 3 (2020), Model S (2016 Facelit), Model X (2017)    |
| MI02   | 3rd Generation Production                                | Model 3 (2021), Model X (2017)                            |
| MI03   | 4th Generation Production                                | Model S (2018), Model X (2018)                            |
| MI04   | 5th Generation Production                                | Model S (2019/2020), Model X (2020/2021)                  |
| MR31   | Tech Package - Mirror -YES                               | Uplevel Mirrors                                           |
| MT300  | Standard Range Rear-Wheel Drive                          | Model 3                                                   |
| MT301  | Standard Range Plus Rear-Wheel Drive                     | Model 3                                                   |
| MT302  | Long Range Rear-Wheel Drive                              | Model 3                                                   |
| MT303  | Long Range All-Wheel Drive                               | Model 3                                                   |
| MT304  | Long Range All-Wheel Drive Performance                   | Model 3                                                   |
| MT305  | Mid Range Rear-Wheel Drive                               | Model 3                                                   |
| MT307  | Mid Range Rear-Wheel Drive                               | Model 3                                                   |
| MT308  | Standard Range Plus Rear-Wheel Drive                     | Model 3 2019 Refresh                                      |
| MT309  | Standard Range Plus Rear-Wheel Drive                     | Model 3 2019 Refresh                                      |
| MT314  | Standard Range Plus Rear-Wheel Drive                     | Model 3 2021 Refresh                                      |
| MT320  | Standard Range Plus Rear-Wheel Drive                     | Model 3 2021 Refresh                                      |
| MT336  | Standard Range Plus Rear-Wheel Drive                     | Model 3 2020 Refresh                                      |
| MT337  | Standard Range Plus Rear-Wheel Drive                     | Model 3 2021 Refresh                                      |
| MT310  | Long Range All-Wheel Drive                               | Model 3                                                   |
| MT311  | Long Range All-Wheel Drive Performance                   | Model 3                                                   |
| MT315  | Long Range All-Wheel Drive                               | Model 3 2021 Refresh                                      |
| MT316  | Long Range All-Wheel Drive                               | Model 3 2021 Refresh                                      |
| MT317  | Long Range All-Wheel Drive Performance                   | Model 3 2021 Refresh                                      |
| MTS01  | Standard Range                                           | Model S                                                   |
| MTS03  | Long Range                                               | Model S                                                   |
| MTS04  | Performance                                              | Model S                                                   |
| MTS05  | Long Range                                               | Model S                                                   |
| MTS06  | Performance                                              | Model S                                                   |
| MTS07  | Long Range Plus                                          | Model S                                                   |
| MTS08  | Performance                                              | Model S                                                   |
| MTS09  | Plaid+                                                   | Model S Refresh 2021                                      |
| MTS10  | Long Range                                               | Model S Refresh 2021                                      |
| MTS11  | Plaid                                                    | Model S Refresh 2021                                      |
| MTX01  | Standard Range                                           | Model X                                                   |
| MTX03  | Long Range                                               | Model X                                                   |
| MTX04  | Performance                                              | Model X                                                   |
| MTX05  | Long Range Plus                                          | Model X                                                   |
| MTX06  | Performance                                              | Model X                                                   |
| MTX07  | Long Range Plus                                          | Model X                                                   |
| MTX08  | Performance                                              | Model X                                                   |
| MTX10  | Long Range                                               | Model X Refresh 2021                                      |
| MTX11  | Plaid                                                    | Model X Refresh 2021                                      |
| MTY01  | Standard Range Rear-Wheel Drive                          | Model Y                                                   |
| MTY02  | Long Range Rear-Wheel Drive                              | Model Y                                                   |
| MTY03  | Long Range All-Wheel Drive                               | Model Y                                                   |
| MTY04  | Long Range All-Wheel Drive Performance                   | Model Y                                                   |
| MTY05  | Long Range All-Wheel Drive Performance                   | Model Y                                                   |
| OSSB   | Safety CA Black                                          |                                                           |
| OSSW   | Safety CA White                                          |                                                           |
| PA00   | No Paint Armor                                           |                                                           |
| PBCW   | Solid White Color                                        |                                                           |
| PBSB   | Solid Black Color                                        |                                                           |
| PBT85  | Performance 85kWh                                        |                                                           |
| PC30   | No Performance Chassis                                   |                                                           |
| PC31   | Performance Chassis                                      |                                                           |
| PF00   | No Performance Legacy Package                            |                                                           |
| PF01   | Performance Legacy Package                               |                                                           |
| PI00   | No Premium Interior                                      |                                                           |
| PI01   | Premium Upgrades Package                                 |                                                           |
| PK00   | Parking Sensors                                          | No Parking Sensors                                        |
| PMAB   | Anza Brown Metallic Color                                |                                                           |
| PMBL   | Obsidian Black Multi-Coat Color                          |                                                           |
| PMMB   | Monterey Blue Metallic Color                             |                                                           |
| PMNG   | Midnight Silver Metallic Color                           |                                                           |
| PMSG   | Green Metallic Color                                     |                                                           |
| PMSS   | San Simeon Silver Metallic Color                         |                                                           |
| PMTG   | Dolphin Grey Metallic Color                              |                                                           |
| PPMR   | Red Multi-Coat Color                                     |                                                           |
| PPSB   | Deep Blue Metallic Color                                 |                                                           |
| PPSR   | Signature Red Color                                      |                                                           |
| PPSW   | Pearl White Multi-Coat Color                             |                                                           |
| PPTI   | Titanium Metallic Color                                  |                                                           |
| PL30   | No Aluminum Pedal                                        |                                                           |
| PL31   | Performance Pedals                                       | Model 3                                                   |
| PRM30  | Partial Premium Interior                                 |                                                           |
| PRM31  | Premium Interior                                         |                                                           |
| PRM3S  | Standard Interior                                        |                                                           |
| PRMY1  | Premium Interior                                         |                                                           |
| PS00   | No Parcel Shelf                                          |                                                           |
| PS01   | Parcel Shelf                                             |                                                           |
| RS3H   | Second Row Seat Rear Seats (Heated)                      | Model 3                                                   |
| PX00   | No Performance Plus Package                              |                                                           |
| PX01   | Performance Plus                                         |                                                           |
| PX4D   |  90 kWh Performance                                      |                                                           |
| PX6D   | Zero to 60 in 2.5 sec                                    |                                                           |
| P85D   | P85D                                                     |                                                           |
| QLBS   | Black Premium Interior                                   |                                                           |
| QLFC   | Cream Premium Interior                                   |                                                           |
| QLFP   | Black Premium Interior                                   |                                                           |
| QLFW   | White Premium Interior                                   |                                                           |
| QLPW   | White Premium Interior                                   |                                                           |
| QLWS   | White Premium Interior                                   |                                                           |
| QNET   | Tan NextGen                                              |                                                           |
| QPBT   | Black Textile Interior                                   |                                                           |
| QPMP   | Black seats                                              |                                                           |
| QTBS   | Black Premium Interior                                   |                                                           |
| QTBW   | White Premium Seats                                      |                                                           |
| QTFC   | Cream Premium Interior                                   |                                                           |
| QTFP   | Black Premium Seats                                      |                                                           |
| QTFW   | White Premium Interior                                   |                                                           |
| QTPB   | Black Leather Tesla Premium Seats                        |                                                           |
| QTPC   | Cream Premium Seats                                      |                                                           |
| QTPP   | Black Premium Seats                                      |                                                           |
| QTPT   | Tan Premium Seats                                        |                                                           |
| QTTB   | Multi-Pattern Black Seats                                |                                                           |
| QTWS   | White Premium Interior                                   |                                                           |
| QVBM   | Multi-Pattern Black Seats                                |                                                           |
| QVPC   | Vegan Cream Seats                                        |                                                           |
| QVPP   | Vegan Cream Seats                                        |                                                           |
| QVSW   | White Tesla Seats                                        |                                                           |
| QXMB   | Black Leather Seat                                       |                                                           |
| RCX0   | No Rear Console                                          |                                                           |
| RCX1   | Rear Console                                             |                                                           |
| RF3G   | Glass Roof                                               | Model 3                                                   |
| RFBK   | Black Roof                                               | Model S                                                   |
| RFBC   | Body Color Roof                                          | Model S                                                   |
| RFFG   | Glass Roof                                               | Model S 2017 Production Refresh                           |
| RFPO   | All Glass Panoramic Roof                                 | Model S 2015 Production Refresh                           |
| RFP2   | Sunroof                                                  | Model S 2016 Production Refresh                           |
| RFPX   | Glass Roof                                               | Model X                                                   |
| RSF1   | Rear Heated Seats                                        |                                                           |
| RU00   | No Range Upgrade                                         |                                                           |
| S01B   | Black Textile Seats                                      |                                                           |
| S02B   | Seat                                                     | BLK Leather                                               |
| S02P   | S02P                                                     |                                                           |
| S02W   | White Seats                                              |                                                           |
| S07W   | White Seats                                              |                                                           |
| S31B   | S31B                                                     |                                                           |
| S32C   | S32C                                                     |                                                           |
| S32P   | S32P                                                     |                                                           |
| S32W   | S32W                                                     |                                                           |
| S3PB   | Seat Black PUR Premium Seats                             |                                                           |
| S3PW   | Seat White PUR Premium Seats                             |                                                           |
| SA3P   | Seat Adjustment - Power                                  | Model 3                                                   |
| SC00   | No Supercharging                                         |                                                           |
| SC01   | Unlimited Free Supercharging Enabled                     | Transfers to the next owner via private sale              |
| SC04   | Pay Per Use Supercharging                                |                                                           |
| SC05   | Unlimited Free Supercharging Currently Enabled           | Not transferable to the next owner                        |
| SC06   | Time Bound Unlimited Free Supercharging                  |                                                           |
| SLR0   | No Rear Spoiler                                          |                                                           |
| SP00   | No Security Package                                      |                                                           |
| SP01   | Security Package                                         |                                                           |
| SR01   | Standard 2nd row                                         | Second Row Seat                                           |
| SR06   | Seven Seat Interior                                      |                                                           |
| SR07   | Standard 2nd row                                         |                                                           |
| ST00   | Non-leather Steering Wheel                               |                                                           |
| ST01   | Non-heated Leather Steering Wheel                        |                                                           |
| ST31   | Steering Wheel                                           | Premium Steering Wheel                                    |
| STCP   | Steering Wheel                                           | Steering Column (Power)                                   |
| STY5S  | Five Seat Interior                                       |                                                           |
| STY7S  | Seven Seat Interior                                      |                                                           |
| SU00   | Standard Suspension                                      |                                                           |
| SU01   | Smart Air Suspension                                     |                                                           |
| SU03   | Suspension Update                                        | Model X 2020                                              |
| SU3C   | Coil Spring Suspension                                   |                                                           |
| T3MA   | Tires M3                                                 | 18 Michelin All Season, Square                            |
| TIC4   | Tires                                                    | All-Season Tires                                          |
| TIG2   | Summer Tires                                             |                                                           |
| TIM7   | Summer Tires                                             |                                                           |
| TIMP   | Tires                                                    | Michelin Primacy 19" Tire                                 |
| TIP0   | All-season Tires                                         | Pirelli Scorpion Zero Asimmetrico 22” Tire                |
| TM00   | Model Trim                                               | General Production Series Vehicle                         |
| TM02   | General Production Signature Trim                        |                                                           |
| TM0A   | ALPHA PRE-PRODUCTION NON-SALEABLE                        |                                                           |
| TM0B   | BETA PRE-PRODUCTION NON-SALEABLE                         |                                                           |
| TM0C   | PRE-PRODUCTION SALEABLE                                  |                                                           |
| TP01   | No Technology Package                                    |                                                           |
| TP01   | Tech Package - No Autopilot                              |                                                           |
| TP02   | Tech Package with Autopilot                              |                                                           |
| TP03   | Tech Package with Enhanced Autopilot                     |                                                           |
| TR00   | No Rear Facing Seats                                     |
| TR01   | Third Row Seating                                        |                                                           |
| TRA1   | Third Row HVAC                                           |                                                           |
| TW00   | No Tow Package                                           |                                                           |
| TW01   | Tow Package                                              |                                                           |
| UM01   | Universal Mobile Charger - US Port (Single)              |                                                           |
| UT3P   | Suede Grey Premium Headliner                             |                                                           |
| UTAB   | Black Alcantara Headliner                                |                                                           |
| UTAW   | Light Headliner                                          |                                                           |
| UTMF   | Headliner                                                |                                                           |
| UTPB   | Dark Headliner                                           |                                                           |
| UTSB   | Dark Headliner                                           |                                                           |
| UTZW   | Light Headliner                                          |                                                           |
| USSB   | Safety                                                   | Safety US Black                                           |
| USSW   | US Safety Kit White                                      |                                                           |
| SLR1   | Carbon Fibre Spoiler                                     | Model 3                                                   |
| SPT31  | Performance Upgrade                                      | Model 3                                                   |
| SPTY1  | Performance Upgrade                                      | Model Y                                                   |
| W32P   | 20" Performance Wheels                                   | Model 3                                                   |
| W32D   | 20" Gray Performance Wheels                              | Model 3                                                   |
| W38B   | 18" Aero Wheels                                          | For the Model 3 and Model Y                               |
| W39B   | 19" Sport Wheels                                         |                                                           |
| WR00   | No Wrap                                                  |                                                           |
| WS90   | 19" Tempest Wheels                                       | Model S Refresh 2021                                      |
| WT19   | 19" Wheels                                               |                                                           |
| WS10   | 21" Arachnid Wheels                                      | Model S Refresh 2021                                      |
| WT20   | 20" Silver Slipstream Wheels                             |                                                           |
| WT22   | 22" Silver Turbine Wheels                                |                                                           |
| WTAB   | 21" Black Arachnid Wheels                                |                                                           |
| WTAS   | 19" Silver Slipstream Wheels                             |                                                           |
| WTDS   | 19" Grey Slipstream Wheels                               |                                                           |
| WTNN   | 20" Nokian Winter Tires (non-studded)                    |                                                           |
| WTNS   | 20" Nokian Winter Tires (studded)                        |                                                           |
| WTP2   | 20" Pirelli Winter Tires                                 |                                                           |
| WTSC   | 20" Sonic Carbon Wheels                                  |                                                           |
| WTSD   | 20" Two-Tone Slipstream Wheels                           |                                                           |
| WTSG   | 21" Turbine Wheels                                       |                                                           |
| WTSP   | 21" Turbine Wheels                                       |                                                           |
| WTSS   | 21" Turbine Wheels                                       |                                                           |
| WTHX   | 20" Turbine Wheels                                       |                                                           |
| WTTG   | 19" Cyclone Wheels                                       |                                                           |
| WTTB   | 19" Cyclone Wheels                                       |                                                           |
| WTTC   | 21" Sonic Carbon Twin Turbine Wheels                     |                                                           |
| WTUT   | 22" Onyx Black Wheels                                    | 22" Ultrasonic Turbine wheels                             |
| WTW2   | 19" Nokian Winter Wheel Set                              |                                                           |
| WTW3   | 19" Pirelli Winter Wheel Set                             |                                                           |
| WTW4   | 19" Winter Tire Set                                      |                                                           |
| WTW5   | 21" Winter Tire Set                                      |                                                           |
| WTW6   | 19" Nokian Winter Tires (studded)                        |                                                           |
| WTW7   | 19" Nokian Winter Tires (non-studded)                    |                                                           |
| WTW8   | 19" Pirelli Winter Tires                                 |                                                           |
| WTX1   | 19" Michelin Primacy Tire Upgrade                        |                                                           |
| WX00   | 20" Cyberstream Wheels                                   | Model X Refresh 2021                                      |
| WX20   | 22" Turbine Wheels                                       | Model X Refresh 2021                                      |
| WXNN   | No 20" Nokian Winter Tires (non-studded)                 |                                                           |
| WXNS   | No 20" Nokian Winter Tires (studded)                     |                                                           |
| WXP2   | No 20" Pirelli Winter Tires                              |                                                           |
| WXW2   | No 19" Wheels with Nokian Winter Tyres                   |                                                           |
| WXW3   | No 19" Wheels with Pirelli Winter Tyres                  |                                                           |
| WXW4   | No 19" Winter Tire Set                                   |                                                           |
| WXW5   | No 21" Winter Tire Set                                   |                                                           |
| WXW6   | No 19" Nokian Winter Tires (studded)                     |                                                           |
| WXW7   | No 19" Nokian Winter Tires (non-studded)                 |                                                           |
| WXW8   | No 19" Pirelli Winter Tires                              |                                                           |
| WY18B  | 18" Aero Wheels                                          |                                                           |
| WY19B  | 19" Sport Wheels                                         |                                                           |
| WY20P  | 20" Performance Wheels                                   |                                                           |
| X001   | Override: Power Liftgate                                 |                                                           |
| X002   | Override: Manual Liftgate                                |                                                           |
| X003   | Maps & Navigation                                        |                                                           |
| X004   | Override: No Navigation                                  |                                                           |
| X007   | Exterior Lights Override: Premium exterior lighting YES  |                                                           |
| X010   | Base Mirrors                                             |                                                           |
| X011   | Override: Homelink                                       |                                                           |
| X012   | Override: No Homelink                                    |                                                           |
| X013   | Override: Satellite Radio                                |                                                           |
| X014   | Override: No Satellite Radio                             |                                                           |
| X019   | Carbon Fiber Spoiler                                     |                                                           |
| X020   | No Performance Exterior                                  |                                                           |
| X021   | No Rear Carbon Fiber Spoiler                             |                                                           |
| X024   | Performance Package                                      |                                                           |
| X025   | No Performance Powertrain                                |                                                           |
| X026   | Door handle                                              | No light handle                                           |
| X027   | Lighted Door Handles                                     | Light handle                                              |
| X028   | Battery Badge                                            | Normal Badging                                            |
| X029   | Remove Battery Badge                                     |                                                           |
| X030   | Override: No Passive Entry Pkg                           |                                                           |
| X031   | Keyless Entry                                            | Passive Entry Pkg                                         |
| X037   | Powerfolding Mirrors                                     |                                                           |
| X039   | DAB Radio                                                |                                                           |
| X040   | No DAB Radio                                             |                                                           |
| X041   | No Auto Presenting Door                                  |                                                           |
| X042   | Auto Presenting Door                                     |                                                           |
| X043   | No Phone Dock Kit                                        |                                                           |
| X044   | Phone Dock Kit                                           |                                                           |
| YF00   | No Yacht Floor                                           |                                                           |
| YF01   | Matching Yacht Floor                                     |                                                           |
| YFCC   | YFCC                                                     |                                                           |
| YFFC   | Integrated Center Console                                |                                                           |
