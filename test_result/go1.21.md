# Test result base one go 1.21

```bash
$ go test -timeout=2h -bench=.

#GithubAPI Routes: 203
   Ace: 48632 Bytes
   Aero: 489592 Bytes
   Bear: 81184 Bytes
   Beego: 150632 Bytes
   Bone: 100976 Bytes
   Chi: 94888 Bytes
   CloudyKitRouter: 93648 Bytes
   Denco: 36344 Bytes
   Echo: 137720 Bytes
   Gin: 58792 Bytes
   GocraftWeb: 94504 Bytes
   Goji: 46416 Bytes
   Gojiv2: 104112 Bytes
   GoJsonRest: 153584 Bytes
   GoRestful: 1240912 Bytes
   GorillaMux: 1319632 Bytes
   GowwwRouter: 78640 Bytes
   HttpRouter: 37088 Bytes
   HttpTreeMux: 78800 Bytes
   Kocha: 787256 Bytes
   LARS: 48592 Bytes
   Macaron: 92752 Bytes
   Martini: 485032 Bytes
   Pat: 21192 Bytes
   Possum: 81816 Bytes
   R2router: 46616 Bytes
   Rivet: 42840 Bytes
   Tango: 54840 Bytes
   TigerTonic: 97456 Bytes
   Traffic: 918704 Bytes
   Vulcan: 439168 Bytes

#GPlusAPI Routes: 13
   Ace: 3664 Bytes
   Aero: 26032 Bytes
   Bear: 7096 Bytes
   Beego: 10256 Bytes
   Bone: 6688 Bytes
   Chi: 8008 Bytes
   CloudyKitRouter: 6728 Bytes
   Denco: 3224 Bytes
   Echo: 11808 Bytes
   Gin: 4544 Bytes
   GocraftWeb: 7480 Bytes
   Goji: 2928 Bytes
   Gojiv2: 7264 Bytes
   GoJsonRest: 11696 Bytes
   GoRestful: 74280 Bytes
   GorillaMux: 66016 Bytes
   GowwwRouter: 5640 Bytes
   HttpRouter: 2760 Bytes
   HttpTreeMux: 7440 Bytes
   Kocha: 128880 Bytes
   LARS: 3656 Bytes
   Macaron: 8632 Bytes
   Martini: 23888 Bytes
   Pat: 1848 Bytes
   Possum: 7152 Bytes
   R2router: 3864 Bytes
   Rivet: 3064 Bytes
   Tango: 5168 Bytes
   TigerTonic: 9392 Bytes
   Traffic: 46192 Bytes
   Vulcan: 25888 Bytes

#ParseAPI Routes: 26
   Ace: 6656 Bytes
   Aero: 28440 Bytes
   Bear: 12216 Bytes
   Beego: 19096 Bytes
   Bone: 11440 Bytes
   Chi: 9656 Bytes
   CloudyKitRouter: 11184 Bytes
   Denco: 4080 Bytes
   Echo: 15088 Bytes
   Gin: 7864 Bytes
   GocraftWeb: 12712 Bytes
   Goji: 5248 Bytes
   Gojiv2: 14272 Bytes
   GoJsonRest: 14608 Bytes
   GoRestful: 116032 Bytes
   GorillaMux: 105448 Bytes
   GowwwRouter: 9280 Bytes
   HttpRouter: 5024 Bytes
   HttpTreeMux: 7848 Bytes
   Kocha: 181712 Bytes
   LARS: 6632 Bytes
   Macaron: 13624 Bytes
   Martini: 45808 Bytes
   Pat: 2552 Bytes
   Possum: 9088 Bytes
   R2router: 6920 Bytes
   Rivet: 5680 Bytes
   Tango: 8920 Bytes
   TigerTonic: 9768 Bytes
   Traffic: 78896 Bytes
   Vulcan: 44880 Bytes

#Static Routes: 157
   HttpServeMux: 14504 Bytes
   Ace: 30648 Bytes
   Aero: 34504 Bytes
   Bear: 34112 Bytes
   Beego: 98008 Bytes
   Bone: 40224 Bytes
   Chi: 83160 Bytes
   CloudyKitRouter: 30376 Bytes
   Denco: 9912 Bytes
   Echo: 97352 Bytes
   Gin: 34344 Bytes
   GocraftWeb: 59376 Bytes
   Goji: 27216 Bytes
   Gojiv2: 106368 Bytes
   GoJsonRest: 137840 Bytes
   GoRestful: 815192 Bytes
   GorillaMux: 582536 Bytes
   GowwwRouter: 24512 Bytes
   HttpRouter: 21680 Bytes
   HttpTreeMux: 73448 Bytes
   Kocha: 123656 Bytes
   LARS: 30640 Bytes
   Macaron: 38560 Bytes
   Martini: 309880 Bytes
   Pat: 19688 Bytes
   Possum: 89136 Bytes
   R2router: 23256 Bytes
   Rivet: 24608 Bytes
   Tango: 28264 Bytes
   TigerTonic: 82872 Bytes
   Traffic: 538032 Bytes
   Vulcan: 368712 Bytes

goos: linux
goarch: amd64
pkg: github.com/julienschmidt/go-http-routing-benchmark
cpu: Intel(R) Xeon(R) CPU E5-2680 v3 @ 2.50GHz
BenchmarkAce_Param                       6452019               179.1 ns/op            32 B/op          1 allocs/op
BenchmarkAero_Param                     21795811                53.66 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Param                      1269483               908.0 ns/op           456 B/op          5 allocs/op
BenchmarkBeego_Param                     1000000              1200 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Param                      1000000              1301 ns/op             688 B/op          5 allocs/op
BenchmarkChi_Param                       1727101               692.1 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_Param          38546190                29.30 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_Param                     7092050               150.2 ns/op            32 B/op          1 allocs/op
BenchmarkEcho_Param                     16422950                73.72 ns/op            0 B/op          0 allocs/op
BenchmarkGin_Param                      17755218                73.12 ns/op            0 B/op          0 allocs/op
BenchmarkGocraftWeb_Param                1000000              1263 ns/op             640 B/op          8 allocs/op
BenchmarkGoji_Param                      1893174               623.3 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_Param                    1000000              1633 ns/op             944 B/op          8 allocs/op
BenchmarkGoJsonRest_Param                1000000              1518 ns/op             617 B/op         13 allocs/op
BenchmarkGoRestful_Param                  168694              6843 ns/op            4120 B/op         12 allocs/op
BenchmarkGorillaMux_Param                1000000              2123 ns/op            1024 B/op          8 allocs/op
BenchmarkGowwwRouter_Param               2672776               474.9 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_Param                9120236               120.9 ns/op            32 B/op          1 allocs/op
BenchmarkHttpTreeMux_Param               1984334               576.7 ns/op           352 B/op          3 allocs/op
BenchmarkKocha_Param                     4170187               287.0 ns/op            56 B/op          3 allocs/op
BenchmarkLARS_Param                     19505224                58.82 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_Param                    378796              3108 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_Param                    283296              5006 ns/op            1096 B/op         12 allocs/op
BenchmarkPat_Param                       1000000              1491 ns/op             512 B/op         10 allocs/op
BenchmarkPossum_Param                    1000000              1182 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_Param                  1707132               672.5 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_Param                     6145848               188.2 ns/op            48 B/op          1 allocs/op
BenchmarkTango_Param                     1289478               924.2 ns/op           192 B/op          6 allocs/op
BenchmarkTigerTonic_Param                 780650              2201 ns/op             712 B/op         14 allocs/op
BenchmarkTraffic_Param                    307780              3942 ns/op            1848 B/op         21 allocs/op
BenchmarkVulcan_Param                    2318997               511.6 ns/op            98 B/op          3 allocs/op
BenchmarkAce_Param5                      2926360               402.0 ns/op           160 B/op          1 allocs/op
BenchmarkAero_Param5                    13968442                84.48 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Param5                     1000000              1266 ns/op             501 B/op          5 allocs/op
BenchmarkBeego_Param5                     975700              1674 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Param5                     1000000              1778 ns/op             736 B/op          5 allocs/op
BenchmarkChi_Param5                      1000000              1018 ns/op             304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_Param5          9036817               133.2 ns/op             0 B/op          0 allocs/op
BenchmarkDenco_Param5                    2906749               412.2 ns/op           160 B/op          1 allocs/op
BenchmarkEcho_Param5                     7578350               159.8 ns/op             0 B/op          0 allocs/op
BenchmarkGin_Param5                      8461772               139.1 ns/op             0 B/op          0 allocs/op
BenchmarkGocraftWeb_Param5                642627              2210 ns/op             912 B/op         11 allocs/op
BenchmarkGoji_Param5                     1317132               909.9 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_Param5                   1000000              2007 ns/op            1008 B/op          8 allocs/op
BenchmarkGoJsonRest_Param5                560368              2968 ns/op            1065 B/op         16 allocs/op
BenchmarkGoRestful_Param5                 176641              6303 ns/op            4216 B/op         12 allocs/op
BenchmarkGorillaMux_Param5                482692              3337 ns/op            1088 B/op          8 allocs/op
BenchmarkGowwwRouter_Param5              2101471               568.4 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_Param5               3554245               336.6 ns/op           160 B/op          1 allocs/op
BenchmarkHttpTreeMux_Param5              1000000              1514 ns/op             576 B/op          6 allocs/op
BenchmarkKocha_Param5                    1000000              1290 ns/op             440 B/op         10 allocs/op
BenchmarkLARS_Param5                    10815243               111.1 ns/op             0 B/op          0 allocs/op
BenchmarkMacaron_Param5                   280082              3604 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_Param5                   189633              6182 ns/op            1256 B/op         13 allocs/op
BenchmarkPat_Param5                       404725              3284 ns/op             800 B/op         24 allocs/op
BenchmarkPossum_Param5                   1000000              1141 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_Param5                 1506246               809.9 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_Param5                    2013402               553.4 ns/op           240 B/op          1 allocs/op
BenchmarkTango_Param5                    1000000              1182 ns/op             312 B/op          6 allocs/op
BenchmarkTigerTonic_Param5                162022              8290 ns/op            2023 B/op         29 allocs/op
BenchmarkTraffic_Param5                   192774              6356 ns/op            2200 B/op         27 allocs/op
BenchmarkVulcan_Param5                   1691179               709.1 ns/op            98 B/op          3 allocs/op
BenchmarkAce_Param20                     1000000              1226 ns/op             640 B/op          1 allocs/op
BenchmarkAero_Param20                   30279655                36.68 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Param20                     335452              3618 ns/op            1665 B/op          5 allocs/op
BenchmarkBeego_Param20                    387476              3429 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Param20                     236234              4690 ns/op            1903 B/op          5 allocs/op
BenchmarkChi_Param20                      871632              1887 ns/op             304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_Param20         1867353               649.3 ns/op             0 B/op          0 allocs/op
BenchmarkDenco_Param20                   1000000              1283 ns/op             640 B/op          1 allocs/op
BenchmarkEcho_Param20                    2435016               487.8 ns/op             0 B/op          0 allocs/op
BenchmarkGin_Param20                     3062786               394.2 ns/op             0 B/op          0 allocs/op
BenchmarkGocraftWeb_Param20               152780              7962 ns/op            3753 B/op         15 allocs/op
BenchmarkGoji_Param20                     425552              3166 ns/op            1246 B/op          2 allocs/op
BenchmarkGojiv2_Param20                   503944              2744 ns/op            1248 B/op          8 allocs/op
BenchmarkGoJsonRest_Param20               119829             10535 ns/op            4419 B/op         20 allocs/op
BenchmarkGoRestful_Param20                 85498             12761 ns/op            6608 B/op         16 allocs/op
BenchmarkGorillaMux_Param20               128068              8213 ns/op            3161 B/op         10 allocs/op
BenchmarkGowwwRouter_Param20             1263472               963.8 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_Param20              1000000              1075 ns/op             640 B/op          1 allocs/op
BenchmarkHttpTreeMux_Param20              155103              6992 ns/op            3160 B/op         10 allocs/op
BenchmarkKocha_Param20                    303073              3846 ns/op            1808 B/op         27 allocs/op
BenchmarkLARS_Param20                    3952384               300.2 ns/op             0 B/op          0 allocs/op
BenchmarkMacaron_Param20                  142520              8454 ns/op            2881 B/op         12 allocs/op
BenchmarkMartini_Param20                   95428             11494 ns/op            3585 B/op         15 allocs/op
BenchmarkPat_Param20                       76419             17473 ns/op            4054 B/op         73 allocs/op
BenchmarkPossum_Param20                  1000000              1204 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_Param20                 270190              4711 ns/op            2216 B/op          6 allocs/op
BenchmarkRivet_Param20                   1000000              2002 ns/op            1024 B/op          1 allocs/op
BenchmarkTango_Param20                    805248              2308 ns/op             808 B/op          6 allocs/op
BenchmarkTigerTonic_Param20                36745             30030 ns/op            8769 B/op         79 allocs/op
BenchmarkTraffic_Param20                   57177             22255 ns/op            7760 B/op         47 allocs/op
BenchmarkVulcan_Param20                  1000000              1175 ns/op              98 B/op          3 allocs/op
BenchmarkAce_ParamWrite                  4349599               278.7 ns/op            40 B/op          2 allocs/op
BenchmarkAero_ParamWrite                13355550                87.15 ns/op            0 B/op          0 allocs/op
BenchmarkBear_ParamWrite                 1268059               906.9 ns/op           456 B/op          5 allocs/op
BenchmarkBeego_ParamWrite                1000000              1272 ns/op             360 B/op          4 allocs/op
BenchmarkBone_ParamWrite                 1000000              1336 ns/op             688 B/op          5 allocs/op
BenchmarkChi_ParamWrite                  1632502               734.7 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_ParamWrite     35653964                32.81 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_ParamWrite                5961639               192.7 ns/op            32 B/op          1 allocs/op
BenchmarkEcho_ParamWrite                 6762825               189.4 ns/op             8 B/op          1 allocs/op
BenchmarkGin_ParamWrite                  9247485               130.9 ns/op             0 B/op          0 allocs/op
BenchmarkGocraftWeb_ParamWrite            831361              1513 ns/op             648 B/op          9 allocs/op
BenchmarkGoji_ParamWrite                 1626736               705.0 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_ParamWrite               1000000              1930 ns/op             976 B/op         10 allocs/op
BenchmarkGoJsonRest_ParamWrite            751910              2406 ns/op            1096 B/op         18 allocs/op
BenchmarkGoRestful_ParamWrite             188198              6433 ns/op            4128 B/op         13 allocs/op
BenchmarkGorillaMux_ParamWrite            893533              2311 ns/op            1024 B/op          8 allocs/op
BenchmarkGowwwRouter_ParamWrite          1000000              1384 ns/op             720 B/op          6 allocs/op
BenchmarkHttpRouter_ParamWrite           7812588               148.1 ns/op            32 B/op          1 allocs/op
BenchmarkHttpTreeMux_ParamWrite          1765268               665.7 ns/op           352 B/op          3 allocs/op
BenchmarkKocha_ParamWrite                3636453               322.8 ns/op            56 B/op          3 allocs/op
BenchmarkLARS_ParamWrite                10312437               110.9 ns/op             0 B/op          0 allocs/op
BenchmarkMacaron_ParamWrite               241134              4353 ns/op            1136 B/op         14 allocs/op
BenchmarkMartini_ParamWrite               197020              5795 ns/op            1168 B/op         16 allocs/op
BenchmarkPat_ParamWrite                   945253              2099 ns/op             936 B/op         14 allocs/op
BenchmarkPossum_ParamWrite               1000000              1099 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_ParamWrite             1716276               661.2 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_ParamWrite                3765733               320.3 ns/op           112 B/op          2 allocs/op
BenchmarkTango_ParamWrite                2536477               449.4 ns/op            96 B/op          3 allocs/op
BenchmarkTigerTonic_ParamWrite            431659              3154 ns/op            1152 B/op         19 allocs/op
BenchmarkTraffic_ParamWrite               272964              4982 ns/op            2272 B/op         25 allocs/op
BenchmarkVulcan_ParamWrite               2372510               498.4 ns/op            98 B/op          3 allocs/op
BenchmarkAce_GithubStatic               13825648                87.63 ns/op            0 B/op          0 allocs/op
BenchmarkAero_GithubStatic              24716251                47.48 ns/op            0 B/op          0 allocs/op
BenchmarkBear_GithubStatic               2369374               498.3 ns/op           120 B/op          3 allocs/op
BenchmarkBeego_GithubStatic              1000000              1227 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GithubStatic                 87819             13521 ns/op            2880 B/op         60 allocs/op
BenchmarkCloudyKitRouter_GithubStatic   19875579                60.89 ns/op            0 B/op          0 allocs/op
BenchmarkChi_GithubStatic                1711728               692.5 ns/op           304 B/op          2 allocs/op
BenchmarkDenco_GithubStatic             35707645                32.68 ns/op            0 B/op          0 allocs/op
BenchmarkEcho_GithubStatic              11338195               107.4 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GithubStatic               14120404                85.76 ns/op            0 B/op          0 allocs/op
BenchmarkGocraftWeb_GithubStatic         1528996               772.3 ns/op           288 B/op          5 allocs/op
BenchmarkGoji_GithubStatic               5168271               230.4 ns/op             0 B/op          0 allocs/op
BenchmarkGojiv2_GithubStatic              817663              1656 ns/op             928 B/op          7 allocs/op
BenchmarkGoRestful_GithubStatic           113898             10575 ns/op            4184 B/op         11 allocs/op
BenchmarkGoJsonRest_GithubStatic         1000000              1119 ns/op             297 B/op         11 allocs/op
BenchmarkGorillaMux_GithubStatic          286216              4894 ns/op             720 B/op          7 allocs/op
BenchmarkGowwwRouter_GithubStatic       14456083                83.23 ns/op            0 B/op          0 allocs/op
BenchmarkHttpRouter_GithubStatic        23074005                50.51 ns/op            0 B/op          0 allocs/op
BenchmarkHttpTreeMux_GithubStatic       19462904                64.60 ns/op            0 B/op          0 allocs/op
BenchmarkKocha_GithubStatic             20379676                60.69 ns/op            0 B/op          0 allocs/op
BenchmarkLARS_GithubStatic              15045196                81.96 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_GithubStatic             527457              2467 ns/op             728 B/op          8 allocs/op
BenchmarkMartini_GithubStatic             160714              8033 ns/op             792 B/op         11 allocs/op
BenchmarkPat_GithubStatic                  91054             11963 ns/op            3648 B/op         76 allocs/op
BenchmarkPossum_GithubStatic             1276282               960.9 ns/op           416 B/op          3 allocs/op
BenchmarkR2router_GithubStatic           3075415               363.0 ns/op           112 B/op          3 allocs/op
BenchmarkRivet_GithubStatic             11863136               101.6 ns/op             0 B/op          0 allocs/op
BenchmarkTango_GithubStatic              1000000              1100 ns/op             192 B/op          6 allocs/op
BenchmarkTigerTonic_GithubStatic         4400856               277.2 ns/op            48 B/op          1 allocs/op
BenchmarkTraffic_GithubStatic              89030             13060 ns/op            4656 B/op         90 allocs/op
BenchmarkVulcan_GithubStatic             1451728               751.5 ns/op            98 B/op          3 allocs/op
BenchmarkAce_GithubParam                 3367014               332.4 ns/op            96 B/op          1 allocs/op
BenchmarkAero_GithubParam               11728627               105.3 ns/op             0 B/op          0 allocs/op
BenchmarkBear_GithubParam                1000000              1059 ns/op             496 B/op          5 allocs/op
BenchmarkBeego_GithubParam               1000000              1455 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GithubParam                 162530              7521 ns/op            1760 B/op         18 allocs/op
BenchmarkChi_GithubParam                 1317514               907.5 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_GithubParam     7913092               151.8 ns/op             0 B/op          0 allocs/op
BenchmarkDenco_GithubParam               3469688               324.9 ns/op           128 B/op          1 allocs/op
BenchmarkEcho_GithubParam                7138958               173.2 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GithubParam                 7924342               144.2 ns/op             0 B/op          0 allocs/op
BenchmarkGocraftWeb_GithubParam           853797              1572 ns/op             704 B/op          9 allocs/op
BenchmarkGoji_GithubParam                1000000              1014 ns/op             336 B/op          2 allocs/op
BenchmarkGojiv2_GithubParam               742087              2537 ns/op            1024 B/op         10 allocs/op
BenchmarkGoJsonRest_GithubParam           834826              2108 ns/op             681 B/op         14 allocs/op
BenchmarkGoRestful_GithubParam             75583             15469 ns/op            4280 B/op         14 allocs/op
BenchmarkGorillaMux_GithubParam           190842              7298 ns/op            1040 B/op          8 allocs/op
BenchmarkGowwwRouter_GithubParam         2071906               563.3 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_GithubParam          4289892               276.5 ns/op            96 B/op          1 allocs/op
BenchmarkHttpTreeMux_GithubParam         1271826               965.4 ns/op           384 B/op          4 allocs/op
BenchmarkKocha_GithubParam               1955174               580.1 ns/op           128 B/op          5 allocs/op
BenchmarkLARS_GithubParam                9024188               132.1 ns/op             0 B/op          0 allocs/op
BenchmarkMacaron_GithubParam              360490              3888 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_GithubParam              119236             10125 ns/op            1176 B/op         13 allocs/op
BenchmarkPat_GithubParam                  134695              9154 ns/op            2304 B/op         42 allocs/op
BenchmarkPossum_GithubParam              1000000              1101 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_GithubParam            1680284               724.7 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_GithubParam               2944600               392.7 ns/op            96 B/op          1 allocs/op
BenchmarkTango_GithubParam               1000000              1288 ns/op             296 B/op          6 allocs/op
BenchmarkTigerTonic_GithubParam           511576              3539 ns/op            1008 B/op         18 allocs/op
BenchmarkTraffic_GithubParam              121856              9665 ns/op            2784 B/op         40 allocs/op
BenchmarkVulcan_GithubParam              1000000              1090 ns/op              98 B/op          3 allocs/op
BenchmarkAce_GithubAll                     18824             67491 ns/op           13792 B/op        167 allocs/op
BenchmarkAero_GithubAll                    50048             24158 ns/op               0 B/op          0 allocs/op
BenchmarkBear_GithubAll                     4680            264277 ns/op           86448 B/op        943 allocs/op
BenchmarkBeego_GithubAll                    4758            339107 ns/op           71456 B/op        609 allocs/op
BenchmarkBone_GithubAll                      396           2910805 ns/op          698784 B/op       8453 allocs/op
BenchmarkChi_GithubAll                      8774            194030 ns/op           61712 B/op        406 allocs/op
BenchmarkCloudyKitRouter_GithubAll         48579             24817 ns/op               0 B/op          0 allocs/op
BenchmarkDenco_GithubAll                   18864             66743 ns/op           20224 B/op        167 allocs/op
BenchmarkEcho_GithubAll                    30819             39312 ns/op               0 B/op          0 allocs/op
BenchmarkGin_GithubAll                     36597             32500 ns/op               0 B/op          0 allocs/op
BenchmarkGocraftWeb_GithubAll               2740            389497 ns/op          130032 B/op       1686 allocs/op
BenchmarkGoji_GithubAll                     2860            488582 ns/op           56112 B/op        334 allocs/op
BenchmarkGojiv2_GithubAll                   1651            751742 ns/op          274768 B/op       3712 allocs/op
BenchmarkGoJsonRest_GithubAll               2700            428189 ns/op          127875 B/op       2737 allocs/op
BenchmarkGoRestful_GithubAll                 481           2437222 ns/op          895528 B/op       2532 allocs/op
BenchmarkGorillaMux_GithubAll                319           3783036 ns/op          199682 B/op       1588 allocs/op
BenchmarkGowwwRouter_GithubAll             10000            110374 ns/op           50768 B/op        334 allocs/op
BenchmarkHttpRouter_GithubAll              23415             51207 ns/op           13792 B/op        167 allocs/op
BenchmarkHttpTreeMux_GithubAll             10000            187968 ns/op           65856 B/op        671 allocs/op
BenchmarkKocha_GithubAll                   10000            120107 ns/op           23304 B/op        843 allocs/op
BenchmarkLARS_GithubAll                    46064             25554 ns/op               0 B/op          0 allocs/op
BenchmarkMacaron_GithubAll                  2128            496566 ns/op          147784 B/op       1624 allocs/op
BenchmarkMartini_GithubAll                   312           3693041 ns/op          231418 B/op       2731 allocs/op
BenchmarkPat_GithubAll                       283           4327362 ns/op         1410624 B/op      22515 allocs/op
BenchmarkPossum_GithubAll                  10000            175645 ns/op           84448 B/op        609 allocs/op
BenchmarkR2router_GithubAll                10000            154076 ns/op           70832 B/op        776 allocs/op
BenchmarkRivet_GithubAll                   14947             78048 ns/op           16272 B/op        167 allocs/op
BenchmarkTango_GithubAll                    5422            273659 ns/op           53849 B/op       1215 allocs/op
BenchmarkTigerTonic_GithubAll               1756            716010 ns/op          174576 B/op       3796 allocs/op
BenchmarkTraffic_GithubAll                   310           3764786 ns/op          819046 B/op      14114 allocs/op
BenchmarkVulcan_GithubAll                   6588            205531 ns/op           19894 B/op        609 allocs/op
BenchmarkAce_GPlusStatic                18821314                62.74 ns/op            0 B/op          0 allocs/op
BenchmarkAero_GPlusStatic               33104586                34.98 ns/op            0 B/op          0 allocs/op
BenchmarkBear_GPlusStatic                3251666               346.4 ns/op           104 B/op          3 allocs/op
BenchmarkBeego_GPlusStatic               1000000              1099 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GPlusStatic                5782683               192.6 ns/op            32 B/op          1 allocs/op
BenchmarkChi_GPlusStatic                 1956270               598.5 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_GPlusStatic    37698682                32.06 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_GPlusStatic              54673414                21.81 ns/op            0 B/op          0 allocs/op
BenchmarkEcho_GPlusStatic               15980792                71.99 ns/op            0 B/op          0 allocs/op
BenchmarkGin_GPlusStatic                19461288                59.69 ns/op            0 B/op          0 allocs/op
BenchmarkGocraftWeb_GPlusStatic          1846340               642.2 ns/op           272 B/op          5 allocs/op
BenchmarkGoji_GPlusStatic                7873600               149.9 ns/op             0 B/op          0 allocs/op
BenchmarkGojiv2_GPlusStatic               819535              1532 ns/op             928 B/op          7 allocs/op
BenchmarkGoJsonRest_GPlusStatic          1302488               928.4 ns/op           297 B/op         11 allocs/op
BenchmarkGoRestful_GPlusStatic            220323              5291 ns/op            3800 B/op         11 allocs/op
BenchmarkGorillaMux_GPlusStatic          1000000              1398 ns/op             720 B/op          7 allocs/op
BenchmarkGowwwRouter_GPlusStatic        37317663                31.02 ns/op            0 B/op          0 allocs/op
BenchmarkHttpRouter_GPlusStatic         45366345                26.81 ns/op            0 B/op          0 allocs/op
BenchmarkHttpTreeMux_GPlusStatic        28504552                41.71 ns/op            0 B/op          0 allocs/op
BenchmarkKocha_GPlusStatic              33012396                35.29 ns/op            0 B/op          0 allocs/op
BenchmarkLARS_GPlusStatic               19925876                57.32 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_GPlusStatic              539442              2308 ns/op             728 B/op          8 allocs/op
BenchmarkMartini_GPlusStatic              356077              4317 ns/op             792 B/op         11 allocs/op
BenchmarkPat_GPlusStatic                 3240465               312.5 ns/op            96 B/op          2 allocs/op
BenchmarkPossum_GPlusStatic              1502677               814.0 ns/op           416 B/op          3 allocs/op
BenchmarkR2router_GPlusStatic            3937726               302.3 ns/op           112 B/op          3 allocs/op
BenchmarkRivet_GPlusStatic              20634534                55.14 ns/op            0 B/op          0 allocs/op
BenchmarkTango_GPlusStatic               1519276               818.9 ns/op           152 B/op          6 allocs/op
BenchmarkTigerTonic_GPlusStatic          6261974               169.1 ns/op            32 B/op          1 allocs/op
BenchmarkTraffic_GPlusStatic              801238              2271 ns/op            1104 B/op         16 allocs/op
BenchmarkVulcan_GPlusStatic              2474402               472.3 ns/op            98 B/op          3 allocs/op
BenchmarkAce_GPlusParam                  4790802               244.1 ns/op            64 B/op          1 allocs/op
BenchmarkAero_GPlusParam                16793863                68.73 ns/op            0 B/op          0 allocs/op
BenchmarkBear_GPlusParam                 1402153               866.1 ns/op           472 B/op          5 allocs/op
BenchmarkBeego_GPlusParam                1000000              1292 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GPlusParam                 1000000              1340 ns/op             688 B/op          5 allocs/op
BenchmarkChi_GPlusParam                  1633000               723.9 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_GPlusParam     19601539                58.37 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_GPlusParam                5317917               223.4 ns/op            64 B/op          1 allocs/op
BenchmarkEcho_GPlusParam                11486857               101.7 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GPlusParam                 10851388               108.1 ns/op             0 B/op          0 allocs/op
BenchmarkGocraftWeb_GPlusParam           1000000              1412 ns/op             640 B/op          8 allocs/op
BenchmarkGoji_GPlusParam                 1743573               789.8 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_GPlusParam               1000000              1936 ns/op             944 B/op          8 allocs/op
BenchmarkGoJsonRest_GPlusParam           1000000              1622 ns/op             617 B/op         13 allocs/op
BenchmarkGoRestful_GPlusParam             180993              5942 ns/op            4120 B/op         12 allocs/op
BenchmarkGorillaMux_GPlusParam            630680              3052 ns/op            1024 B/op          8 allocs/op
BenchmarkGowwwRouter_GPlusParam          2079357               568.6 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_GPlusParam           5615090               183.3 ns/op            64 B/op          1 allocs/op
BenchmarkHttpTreeMux_GPlusParam          1881643               639.4 ns/op           352 B/op          3 allocs/op
BenchmarkKocha_GPlusParam                3845634               320.3 ns/op            56 B/op          3 allocs/op
BenchmarkLARS_GPlusParam                14615773                87.81 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_GPlusParam               363648              3164 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_GPlusParam               266928              5177 ns/op            1096 B/op         12 allocs/op
BenchmarkPat_GPlusParam                  1000000              1607 ns/op             552 B/op         10 allocs/op
BenchmarkPossum_GPlusParam               1000000              1093 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_GPlusParam             1965327               614.5 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_GPlusParam                5246467               214.1 ns/op            48 B/op          1 allocs/op
BenchmarkTango_GPlusParam                1207700              1011 ns/op             216 B/op          6 allocs/op
BenchmarkTigerTonic_GPlusParam            787548              2410 ns/op             792 B/op         14 allocs/op
BenchmarkTraffic_GPlusParam               267148              4416 ns/op            1864 B/op         21 allocs/op
BenchmarkVulcan_GPlusParam               1692349               682.2 ns/op            98 B/op          3 allocs/op
BenchmarkAce_GPlus2Params                4226156               271.0 ns/op            64 B/op          1 allocs/op
BenchmarkAero_GPlus2Params              11492668               101.5 ns/op             0 B/op          0 allocs/op
BenchmarkBear_GPlus2Params               1000000              1021 ns/op             496 B/op          5 allocs/op
BenchmarkBeego_GPlus2Params              1000000              1551 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GPlus2Params                435802              3914 ns/op            1040 B/op          9 allocs/op
BenchmarkChi_GPlus2Params                1273297               958.8 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_GPlus2Params   11485711               103.4 ns/op             0 B/op          0 allocs/op
BenchmarkDenco_GPlus2Params              4146573               280.7 ns/op            64 B/op          1 allocs/op
BenchmarkEcho_GPlus2Params               7866920               147.4 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GPlus2Params                9286442               127.3 ns/op             0 B/op          0 allocs/op
BenchmarkGocraftWeb_GPlus2Params          876812              1535 ns/op             704 B/op          9 allocs/op
BenchmarkGoji_GPlus2Params               1236824               932.0 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_GPlus2Params              806492              2383 ns/op            1024 B/op         11 allocs/op
BenchmarkGoJsonRest_GPlus2Params          912810              1911 ns/op             681 B/op         14 allocs/op
BenchmarkGoRestful_GPlus2Params           176052              6196 ns/op            4312 B/op         14 allocs/op
BenchmarkGorillaMux_GPlus2Params          252418              5661 ns/op            1040 B/op          8 allocs/op
BenchmarkGowwwRouter_GPlus2Params        2250325               516.4 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_GPlus2Params         5660241               204.0 ns/op            64 B/op          1 allocs/op
BenchmarkHttpTreeMux_GPlus2Params        1342579               854.3 ns/op           384 B/op          4 allocs/op
BenchmarkKocha_GPlus2Params              2039354               587.8 ns/op           128 B/op          5 allocs/op
BenchmarkLARS_GPlus2Params              10942212               108.8 ns/op             0 B/op          0 allocs/op
BenchmarkMacaron_GPlus2Params             326450              3310 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_GPlus2Params             117838              9356 ns/op            1224 B/op         15 allocs/op
BenchmarkPat_GPlus2Params                 181213              6141 ns/op            2080 B/op         28 allocs/op
BenchmarkPossum_GPlus2Params             1000000              1095 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_GPlus2Params           1743801               719.4 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_GPlus2Params              3400540               370.3 ns/op            96 B/op          1 allocs/op
BenchmarkTango_GPlus2Params              1000000              1098 ns/op             296 B/op          6 allocs/op
BenchmarkTigerTonic_GPlus2Params          429789              3713 ns/op            1088 B/op         18 allocs/op
BenchmarkTraffic_GPlus2Params             151755              8461 ns/op            2240 B/op         28 allocs/op
BenchmarkVulcan_GPlus2Params             1000000              1065 ns/op              98 B/op          3 allocs/op
BenchmarkAce_GPlusAll                     476296              3266 ns/op             640 B/op         11 allocs/op
BenchmarkAero_GPlusAll                   1000000              1066 ns/op               0 B/op          0 allocs/op
BenchmarkBear_GPlusAll                     83523             12093 ns/op            5488 B/op         61 allocs/op
BenchmarkBeego_GPlusAll                    67281             18932 ns/op            4576 B/op         39 allocs/op
BenchmarkBone_GPlusAll                     36813             32227 ns/op           10336 B/op         98 allocs/op
BenchmarkChi_GPlusAll                     109454             10630 ns/op            3952 B/op         26 allocs/op
BenchmarkCloudyKitRouter_GPlusAll        1215610              1008 ns/op               0 B/op          0 allocs/op
BenchmarkDenco_GPlusAll                   400045              3384 ns/op             672 B/op         11 allocs/op
BenchmarkEcho_GPlusAll                    781538              1615 ns/op               0 B/op          0 allocs/op
BenchmarkGin_GPlusAll                     830475              1410 ns/op               0 B/op          0 allocs/op
BenchmarkGocraftWeb_GPlusAll               60067             16981 ns/op            7936 B/op        103 allocs/op
BenchmarkGoji_GPlusAll                    124766              9988 ns/op            3696 B/op         22 allocs/op
BenchmarkGojiv2_GPlusAll                   46234             25765 ns/op           12624 B/op        115 allocs/op
BenchmarkGoJsonRest_GPlusAll               52774             22041 ns/op            7701 B/op        170 allocs/op
BenchmarkGoRestful_GPlusAll                14617             80681 ns/op           54584 B/op        166 allocs/op
BenchmarkGorillaMux_GPlusAll               26931             44778 ns/op           12784 B/op        102 allocs/op
BenchmarkGowwwRouter_GPlusAll             166388              6249 ns/op            3344 B/op         22 allocs/op
BenchmarkHttpRouter_GPlusAll              780874              2254 ns/op             640 B/op         11 allocs/op
BenchmarkHttpTreeMux_GPlusAll             142724              9089 ns/op            4032 B/op         38 allocs/op
BenchmarkKocha_GPlusAll                   309416              5286 ns/op             976 B/op         43 allocs/op
BenchmarkLARS_GPlusAll                   1000000              1094 ns/op               0 B/op          0 allocs/op
BenchmarkMacaron_GPlusAll                  39723             29068 ns/op            9464 B/op        104 allocs/op
BenchmarkMartini_GPlusAll                  14198             91217 ns/op           14328 B/op        171 allocs/op
BenchmarkPat_GPlusAll                      21333             56367 ns/op           14696 B/op        242 allocs/op
BenchmarkPossum_GPlusAll                  103368             10965 ns/op            5408 B/op         39 allocs/op
BenchmarkR2router_GPlusAll                140682              9818 ns/op            4624 B/op         50 allocs/op
BenchmarkRivet_GPlusAll                   455911              3315 ns/op             768 B/op         11 allocs/op
BenchmarkTango_GPlusAll                    83803             13933 ns/op            3008 B/op         78 allocs/op
BenchmarkTigerTonic_GPlusAll               31994             38987 ns/op           10648 B/op        210 allocs/op
BenchmarkTraffic_GPlusAll                  16267             80325 ns/op           26144 B/op        341 allocs/op
BenchmarkVulcan_GPlusAll                  126238              9893 ns/op            1274 B/op         39 allocs/op
BenchmarkAce_ParseStatic                18910560                62.71 ns/op            0 B/op          0 allocs/op
BenchmarkAero_ParseStatic               30278011                38.59 ns/op            0 B/op          0 allocs/op
BenchmarkBear_ParseStatic                2746058               429.6 ns/op           120 B/op          3 allocs/op
BenchmarkBeego_ParseStatic               1000000              1111 ns/op             352 B/op          3 allocs/op
BenchmarkBone_ParseStatic                1812728               648.4 ns/op           144 B/op          3 allocs/op
BenchmarkChi_ParseStatic                 1795668               691.1 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_ParseStatic    35170952                32.57 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_ParseStatic              32361902                35.90 ns/op            0 B/op          0 allocs/op
BenchmarkEcho_ParseStatic               16493701                70.52 ns/op            0 B/op          0 allocs/op
BenchmarkGin_ParseStatic                20067567                63.62 ns/op            0 B/op          0 allocs/op
BenchmarkGocraftWeb_ParseStatic          1421004               717.8 ns/op           288 B/op          5 allocs/op
BenchmarkGoji_ParseStatic                6198284               205.3 ns/op             0 B/op          0 allocs/op
BenchmarkGojiv2_ParseStatic               820993              1652 ns/op             928 B/op          7 allocs/op
BenchmarkGoJsonRest_ParseStatic          1237442               937.6 ns/op           297 B/op         11 allocs/op
BenchmarkGoRestful_ParseStatic            170389              6238 ns/op            4184 B/op         11 allocs/op
BenchmarkGorillaMux_ParseStatic          1000000              1707 ns/op             720 B/op          7 allocs/op
BenchmarkGowwwRouter_ParseStatic        36079972                31.77 ns/op            0 B/op          0 allocs/op
BenchmarkHttpRouter_ParseStatic         45696668                26.17 ns/op            0 B/op          0 allocs/op
BenchmarkHttpTreeMux_ParseStatic        19145356                63.35 ns/op            0 B/op          0 allocs/op
BenchmarkKocha_ParseStatic              29028990                37.27 ns/op            0 B/op          0 allocs/op
BenchmarkLARS_ParseStatic               20034183                61.26 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_ParseStatic              547222              2340 ns/op             728 B/op          8 allocs/op
BenchmarkMartini_ParseStatic              313550              4332 ns/op             792 B/op         11 allocs/op
BenchmarkPat_ParseStatic                 1608202               740.3 ns/op           240 B/op          5 allocs/op
BenchmarkPossum_ParseStatic              1479087               900.4 ns/op           416 B/op          3 allocs/op
BenchmarkR2router_ParseStatic            3046558               360.4 ns/op           112 B/op          3 allocs/op
BenchmarkRivet_ParseStatic              19991053                63.12 ns/op            0 B/op          0 allocs/op
BenchmarkTango_ParseStatic               1264461               890.9 ns/op           192 B/op          6 allocs/op
BenchmarkTigerTonic_ParseStatic          4135165               269.0 ns/op            48 B/op          1 allocs/op
BenchmarkTraffic_ParseStatic              495602              2795 ns/op            1248 B/op         19 allocs/op
BenchmarkVulcan_ParseStatic              2263950               558.9 ns/op            98 B/op          3 allocs/op
BenchmarkAce_ParseParam                  4794577               218.1 ns/op            64 B/op          1 allocs/op
BenchmarkAero_ParseParam                20941554                58.55 ns/op            0 B/op          0 allocs/op
BenchmarkBear_ParseParam                 1360154               890.9 ns/op           467 B/op          5 allocs/op
BenchmarkBeego_ParseParam                1000000              1170 ns/op             352 B/op          3 allocs/op
BenchmarkBone_ParseParam                 1000000              1521 ns/op             768 B/op          6 allocs/op
BenchmarkChi_ParseParam                  1647656               710.4 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_ParseParam     27303973                45.13 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_ParseParam                4858843               216.5 ns/op            64 B/op          1 allocs/op
BenchmarkEcho_ParseParam                12881325                88.74 ns/op            0 B/op          0 allocs/op
BenchmarkGin_ParseParam                 15886648                75.22 ns/op            0 B/op          0 allocs/op
BenchmarkGocraftWeb_ParseParam           1000000              1259 ns/op             656 B/op          8 allocs/op
BenchmarkGoji_ParseParam                 1581649               744.0 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_ParseParam               1000000              2045 ns/op             976 B/op          9 allocs/op
BenchmarkGoJsonRest_ParseParam           1000000              1531 ns/op             617 B/op         13 allocs/op
BenchmarkGoRestful_ParseParam             189870              6754 ns/op            4504 B/op         12 allocs/op
BenchmarkGorillaMux_ParseParam            893936              2406 ns/op            1024 B/op          8 allocs/op
BenchmarkGowwwRouter_ParseParam          2413303               464.6 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_ParseParam           6956554               174.2 ns/op            64 B/op          1 allocs/op
BenchmarkHttpTreeMux_ParseParam          2025099               631.4 ns/op           352 B/op          3 allocs/op
BenchmarkKocha_ParseParam                4079244               302.3 ns/op            56 B/op          3 allocs/op
BenchmarkLARS_ParseParam                18760250                64.77 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_ParseParam               382255              3248 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_ParseParam               269246              5449 ns/op            1096 B/op         12 allocs/op
BenchmarkPat_ParseParam                   775598              2536 ns/op             952 B/op         13 allocs/op
BenchmarkPossum_ParseParam               1000000              1300 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_ParseParam             1535202               763.7 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_ParseParam                5978270               213.8 ns/op            48 B/op          1 allocs/op
BenchmarkTango_ParseParam                1262524               962.3 ns/op           224 B/op          6 allocs/op
BenchmarkTigerTonic_ParseParam            782044              2205 ns/op             720 B/op         13 allocs/op
BenchmarkTraffic_ParseParam               306548              3861 ns/op            1888 B/op         21 allocs/op
BenchmarkVulcan_ParseParam               1881458               626.8 ns/op            98 B/op          3 allocs/op
BenchmarkAce_Parse2Params                4501401               246.1 ns/op            64 B/op          1 allocs/op
BenchmarkAero_Parse2Params              16048353                71.98 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Parse2Params               1231596              1173 ns/op             496 B/op          5 allocs/op
BenchmarkBeego_Parse2Params              1000000              1373 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Parse2Params               1000000              1728 ns/op             720 B/op          5 allocs/op
BenchmarkChi_Parse2Params                1358080               763.9 ns/op           304 B/op          2 allocs/op
BenchmarkCloudyKitRouter_Parse2Params   17159834                69.41 ns/op            0 B/op          0 allocs/op
BenchmarkDenco_Parse2Params              4482463               246.7 ns/op            64 B/op          1 allocs/op
BenchmarkEcho_Parse2Params              11224530               107.6 ns/op             0 B/op          0 allocs/op
BenchmarkGin_Parse2Params               12676297                96.67 ns/op            0 B/op          0 allocs/op
BenchmarkGocraftWeb_Parse2Params          796777              1591 ns/op             704 B/op          9 allocs/op
BenchmarkGoji_Parse2Params               1382092               817.8 ns/op           336 B/op          2 allocs/op
BenchmarkGojiv2_Parse2Params             1000000              1865 ns/op             960 B/op          8 allocs/op
BenchmarkGoJsonRest_Parse2Params         1000000              1873 ns/op             681 B/op         14 allocs/op
BenchmarkGoRestful_Parse2Params           157021              7371 ns/op            4856 B/op         12 allocs/op
BenchmarkGorillaMux_Parse2Params          620101              2721 ns/op            1040 B/op          8 allocs/op
BenchmarkGowwwRouter_Parse2Params        2353862               499.0 ns/op           304 B/op          2 allocs/op
BenchmarkHttpRouter_Parse2Params         5980803               191.5 ns/op            64 B/op          1 allocs/op
BenchmarkHttpTreeMux_Parse2Params        1338160               888.9 ns/op           384 B/op          4 allocs/op
BenchmarkKocha_Parse2Params              2108691               567.5 ns/op           128 B/op          5 allocs/op
BenchmarkLARS_Parse2Params              13680907                85.67 ns/op            0 B/op          0 allocs/op
BenchmarkMacaron_Parse2Params             359854              3406 ns/op            1064 B/op         10 allocs/op
BenchmarkMartini_Parse2Params             235260              5213 ns/op            1176 B/op         13 allocs/op
BenchmarkPat_Parse2Params                 762854              2433 ns/op             712 B/op         14 allocs/op
BenchmarkPossum_Parse2Params             1000000              1258 ns/op             496 B/op          5 allocs/op
BenchmarkR2router_Parse2Params           1643000               722.6 ns/op           400 B/op          4 allocs/op
BenchmarkRivet_Parse2Params              4004480               309.8 ns/op            96 B/op          1 allocs/op
BenchmarkTango_Parse2Params              1000000              1103 ns/op             264 B/op          6 allocs/op
BenchmarkTigerTonic_Parse2Params          395208              3839 ns/op            1056 B/op         18 allocs/op
BenchmarkTraffic_Parse2Params             246099              5191 ns/op            1936 B/op         22 allocs/op
BenchmarkVulcan_Parse2Params             1577619               780.4 ns/op            98 B/op          3 allocs/op
BenchmarkAce_ParseAll                     313597              4866 ns/op             640 B/op         16 allocs/op
BenchmarkAero_ParseAll                    670203              1774 ns/op               0 B/op          0 allocs/op
BenchmarkBear_ParseAll                     49986             22594 ns/op            8920 B/op        110 allocs/op
BenchmarkBeego_ParseAll                    36178             34917 ns/op            9152 B/op         78 allocs/op
BenchmarkBone_ParseAll                     29697             39495 ns/op           14160 B/op        131 allocs/op
BenchmarkChi_ParseAll                      53862             22689 ns/op            7904 B/op         52 allocs/op
BenchmarkCloudyKitRouter_ParseAll         814131              1415 ns/op               0 B/op          0 allocs/op
BenchmarkDenco_ParseAll                   273775              4834 ns/op             928 B/op         16 allocs/op
BenchmarkEcho_ParseAll                    366046              3078 ns/op               0 B/op          0 allocs/op
BenchmarkGin_ParseAll                     482248              2494 ns/op               0 B/op          0 allocs/op
BenchmarkGocraftWeb_ParseAll               35490             32912 ns/op           13520 B/op        181 allocs/op
BenchmarkGoji_ParseAll                     64188             17218 ns/op            5376 B/op         32 allocs/op
BenchmarkGojiv2_ParseAll                   24278             48805 ns/op           24464 B/op        199 allocs/op
BenchmarkGoJsonRest_ParseAll               28311             41343 ns/op           13034 B/op        321 allocs/op
BenchmarkGoRestful_ParseAll                 9066            195412 ns/op          115728 B/op        302 allocs/op
BenchmarkGorillaMux_ParseAll               12980             94035 ns/op           23632 B/op        198 allocs/op
BenchmarkGowwwRouter_ParseAll             118940             10064 ns/op            4864 B/op         32 allocs/op
BenchmarkHttpRouter_ParseAll              506048              3420 ns/op             640 B/op         16 allocs/op
BenchmarkHttpTreeMux_ParseAll              84568             13931 ns/op            5728 B/op         51 allocs/op
BenchmarkKocha_ParseAll                   179552              7607 ns/op            1112 B/op         54 allocs/op
BenchmarkLARS_ParseAll                    534013              2193 ns/op               0 B/op          0 allocs/op
BenchmarkMacaron_ParseAll                  18109             64628 ns/op           18928 B/op        208 allocs/op
BenchmarkMartini_ParseAll                  10000            150901 ns/op           25696 B/op        305 allocs/op
BenchmarkPat_ParseAll                      21393             55511 ns/op           14688 B/op        288 allocs/op
BenchmarkPossum_ParseAll                   47971             24543 ns/op           10816 B/op         78 allocs/op
BenchmarkR2router_ParseAll                 65624             16481 ns/op            7520 B/op         94 allocs/op
BenchmarkRivet_ParseAll                   302934              5085 ns/op             912 B/op         16 allocs/op
BenchmarkTango_ParseAll                    41925             28887 ns/op            5864 B/op        156 allocs/op
BenchmarkTigerTonic_ParseAll               20854             57902 ns/op           14880 B/op        294 allocs/op
BenchmarkTraffic_ParseAll                  10000            122396 ns/op           45312 B/op        605 allocs/op
BenchmarkVulcan_ParseAll                   62055             20033 ns/op            2548 B/op         78 allocs/op
BenchmarkAce_StaticAll                     56728             21971 ns/op               0 B/op          0 allocs/op
BenchmarkAero_StaticAll                   113079             10752 ns/op               0 B/op          0 allocs/op
BenchmarkHttpServeMux_StaticAll            44296             27416 ns/op               0 B/op          0 allocs/op
BenchmarkBeego_StaticAll                    5647            233515 ns/op           55264 B/op        471 allocs/op
BenchmarkBear_StaticAll                    13179             90354 ns/op           19960 B/op        469 allocs/op
BenchmarkBone_StaticAll                    19137             59671 ns/op               0 B/op          0 allocs/op
BenchmarkChi_StaticAll                     10000            134702 ns/op           47728 B/op        314 allocs/op
BenchmarkCloudyKitRouter_StaticAll         65962             18464 ns/op               0 B/op          0 allocs/op
BenchmarkDenco_StaticAll                  183994              6900 ns/op               0 B/op          0 allocs/op
BenchmarkEcho_StaticAll                    43966             27750 ns/op               0 B/op          0 allocs/op
BenchmarkGin_StaticAll                     53817             22445 ns/op               0 B/op          0 allocs/op
BenchmarkGocraftWeb_StaticAll              10000            135123 ns/op           45056 B/op        785 allocs/op
BenchmarkGoji_StaticAll                    22576             51925 ns/op               0 B/op          0 allocs/op
BenchmarkGojiv2_StaticAll                   3794            318248 ns/op          145696 B/op       1099 allocs/op
BenchmarkGoJsonRest_StaticAll               6590            224126 ns/op           46629 B/op       1727 allocs/op
BenchmarkGoRestful_StaticAll                 765           1442440 ns/op          602040 B/op       1741 allocs/op
BenchmarkGorillaMux_StaticAll               1339            993232 ns/op          113041 B/op       1099 allocs/op
BenchmarkGowwwRouter_StaticAll             57928             20127 ns/op               0 B/op          0 allocs/op
BenchmarkHttpRouter_StaticAll              86230             13894 ns/op               0 B/op          0 allocs/op
BenchmarkHttpTreeMux_StaticAll             83485             13855 ns/op               0 B/op          0 allocs/op
BenchmarkKocha_StaticAll                   79626             15319 ns/op               0 B/op          0 allocs/op
BenchmarkLARS_StaticAll                    57958             21065 ns/op               0 B/op          0 allocs/op
BenchmarkMacaron_StaticAll                  2982            390403 ns/op          114296 B/op       1256 allocs/op
BenchmarkMartini_StaticAll                   660           1780814 ns/op          129209 B/op       2031 allocs/op
BenchmarkPat_StaticAll                       454           2647029 ns/op          602832 B/op      12559 allocs/op
BenchmarkPossum_StaticAll                  10000            148229 ns/op           65312 B/op        471 allocs/op
BenchmarkR2router_StaticAll                18604             65906 ns/op           17584 B/op        471 allocs/op
BenchmarkRivet_StaticAll                   42805             27927 ns/op               0 B/op          0 allocs/op
BenchmarkTango_StaticAll                    7549            207237 ns/op           31272 B/op        942 allocs/op
BenchmarkTigerTonic_StaticAll              23493             50491 ns/op            7376 B/op        157 allocs/op
BenchmarkTraffic_StaticAll                   454           2536613 ns/op          753606 B/op      14601 allocs/op
BenchmarkVulcan_StaticAll                   9640            150665 ns/op           15386 B/op        471 allocs/op
PASS
ok      github.com/julienschmidt/go-http-routing-benchmark      783.307s
```

---

## Bench specific frameworks

```bash
$ go test -timeout=2h -bench="Gin|HttpRouter|GorillaMux"
#GithubAPI Routes: 203
   Gin: 58792 Bytes
   GorillaMux: 1319632 Bytes
   HttpRouter: 37088 Bytes

#GPlusAPI Routes: 13
   Gin: 4544 Bytes
   GorillaMux: 66016 Bytes
   HttpRouter: 2760 Bytes

#ParseAPI Routes: 26
   Gin: 7864 Bytes
   GorillaMux: 105448 Bytes
   HttpRouter: 5024 Bytes

#Static Routes: 157
   Gin: 34344 Bytes
   GorillaMux: 582536 Bytes
   HttpRouter: 21680 Bytes

goos: linux
goarch: amd64
pkg: github.com/julienschmidt/go-http-routing-benchmark
cpu: Intel(R) Xeon(R) CPU E5-2680 v3 @ 2.50GHz
BenchmarkGin_Param                      18149817                70.69 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_Param                 637980              2091 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_Param                9536311               115.9 ns/op            32 B/op          1 allocs/op
BenchmarkGin_Param5                      8425536               139.9 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_Param5                406456              2925 ns/op            1088 B/op          8 allocs/op
BenchmarkHttpRouter_Param5               3812049               293.5 ns/op           160 B/op          1 allocs/op
BenchmarkGin_Param20                     3061050               385.1 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_Param20               189088              6446 ns/op            3161 B/op         10 allocs/op
BenchmarkHttpRouter_Param20              1437646               843.2 ns/op           640 B/op          1 allocs/op
BenchmarkGin_ParamWrite                  8960340               130.8 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_ParamWrite            638228              1863 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_ParamWrite           8399678               135.2 ns/op            32 B/op          1 allocs/op
BenchmarkGin_GithubStatic               15591288                76.47 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_GithubStatic          245906              4826 ns/op             720 B/op          7 allocs/op
BenchmarkHttpRouter_GithubStatic        22750503                51.83 ns/op            0 B/op          0 allocs/op
BenchmarkGin_GithubParam                 7704309               153.3 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_GithubParam           147608              7175 ns/op            1040 B/op          8 allocs/op
BenchmarkHttpRouter_GithubParam          4804894               241.6 ns/op            96 B/op          1 allocs/op
BenchmarkGin_GithubAll                     36452             32221 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_GithubAll                291           4029088 ns/op          199686 B/op       1588 allocs/op
BenchmarkHttpRouter_GithubAll              24703             45776 ns/op           13792 B/op        167 allocs/op
BenchmarkGin_GPlusStatic                19743370                65.66 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlusStatic           850534              1352 ns/op             720 B/op          7 allocs/op
BenchmarkHttpRouter_GPlusStatic         45659998                24.99 ns/op            0 B/op          0 allocs/op
BenchmarkGin_GPlusParam                 12595869                97.18 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlusParam            425071              2870 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_GPlusParam           6671218               170.8 ns/op            64 B/op          1 allocs/op
BenchmarkGin_GPlus2Params                9642994               118.8 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlus2Params          186552              5415 ns/op            1040 B/op          8 allocs/op
BenchmarkHttpRouter_GPlus2Params         5837604               193.1 ns/op            64 B/op          1 allocs/op
BenchmarkGin_GPlusAll                     963072              1345 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlusAll               29246             38806 ns/op           12784 B/op        102 allocs/op
BenchmarkHttpRouter_GPlusAll              589197              2028 ns/op             640 B/op         11 allocs/op
BenchmarkGin_ParseStatic                20747340                62.25 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_ParseStatic           791524              1668 ns/op             720 B/op          7 allocs/op
BenchmarkHttpRouter_ParseStatic         40363404                28.06 ns/op            0 B/op          0 allocs/op
BenchmarkGin_ParseParam                 15502348                75.16 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_ParseParam            573919              1904 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_ParseParam           7162570               150.8 ns/op            64 B/op          1 allocs/op
BenchmarkGin_Parse2Params               12881224                92.76 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_Parse2Params          492934              2450 ns/op            1040 B/op          8 allocs/op
BenchmarkHttpRouter_Parse2Params         6657480               175.9 ns/op            64 B/op          1 allocs/op
BenchmarkGin_ParseAll                     512979              2386 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_ParseAll               14568             76202 ns/op           23632 B/op        198 allocs/op
BenchmarkHttpRouter_ParseAll              424964              2808 ns/op             640 B/op         16 allocs/op
BenchmarkGin_StaticAll                     58736             20745 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_StaticAll               1236            948720 ns/op          113043 B/op       1099 allocs/op
BenchmarkHttpRouter_StaticAll              88072             13153 ns/op               0 B/op          0 allocs/op
PASS
ok      github.com/julienschmidt/go-http-routing-benchmark      75.120s
$ go test -timeout=2h -bench="Gin|HttpRouter|GorillaMux|Aero|Beego|Bear|Chi|Echo|Bone"
#GithubAPI Routes: 203
   Aero: 489480 Bytes
   Bear: 81184 Bytes
   Beego: 150632 Bytes
   Bone: 100976 Bytes
   Chi: 94888 Bytes
   Echo: 137720 Bytes
   Gin: 58792 Bytes
   GorillaMux: 1319632 Bytes
   HttpRouter: 37088 Bytes

#GPlusAPI Routes: 13
   Aero: 26032 Bytes
   Bear: 7096 Bytes
   Beego: 10256 Bytes
   Bone: 6688 Bytes
   Chi: 8008 Bytes
   Echo: 11808 Bytes
   Gin: 4544 Bytes
   GorillaMux: 66016 Bytes
   HttpRouter: 2760 Bytes

#ParseAPI Routes: 26
   Aero: 28728 Bytes
   Bear: 12216 Bytes
   Beego: 19096 Bytes
   Bone: 11440 Bytes
   Chi: 9656 Bytes
   Echo: 15984 Bytes
   Gin: 7864 Bytes
   GorillaMux: 105448 Bytes
   HttpRouter: 5024 Bytes

#Static Routes: 157
   Aero: 34504 Bytes
   Bear: 34320 Bytes
   Beego: 98008 Bytes
   Bone: 40224 Bytes
   Chi: 83160 Bytes
   Echo: 97352 Bytes
   Gin: 34344 Bytes
   GorillaMux: 582536 Bytes
   HttpRouter: 21680 Bytes

goos: linux
goarch: amd64
pkg: github.com/julienschmidt/go-http-routing-benchmark
cpu: Intel(R) Xeon(R) CPU E5-2680 v3 @ 2.50GHz
BenchmarkAero_Param                     24331818                50.85 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Param                      1567267               767.3 ns/op           456 B/op          5 allocs/op
BenchmarkBeego_Param                     1000000              1172 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Param                      1013786              1110 ns/op             688 B/op          5 allocs/op
BenchmarkChi_Param                       1893906               665.6 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_Param                     18140914                68.77 ns/op            0 B/op          0 allocs/op
BenchmarkGin_Param                      18164676                67.67 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_Param                 661210              1897 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_Param                8932074               116.6 ns/op            32 B/op          1 allocs/op
BenchmarkAero_Param5                    13646793                86.66 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Param5                     1079034              1201 ns/op             501 B/op          5 allocs/op
BenchmarkBeego_Param5                     821578              1343 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Param5                      797929              1533 ns/op             736 B/op          5 allocs/op
BenchmarkChi_Param5                      1344922               917.7 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_Param5                     8165683               151.4 ns/op             0 B/op          0 allocs/op
BenchmarkGin_Param5                      8635444               140.5 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_Param5                343662              3052 ns/op            1088 B/op          8 allocs/op
BenchmarkHttpRouter_Param5               4098952               292.6 ns/op           160 B/op          1 allocs/op
BenchmarkAero_Param20                   35759179                34.30 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Param20                     362151              3682 ns/op            1665 B/op          5 allocs/op
BenchmarkBeego_Param20                    451918              3409 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Param20                     258646              4208 ns/op            1903 B/op          5 allocs/op
BenchmarkChi_Param20                      919018              1843 ns/op             304 B/op          2 allocs/op
BenchmarkEcho_Param20                    2670604               499.3 ns/op             0 B/op          0 allocs/op
BenchmarkGin_Param20                     2928756               400.5 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_Param20               135004              8200 ns/op            3161 B/op         10 allocs/op
BenchmarkHttpRouter_Param20              1231068               964.3 ns/op           640 B/op          1 allocs/op
BenchmarkAero_ParamWrite                13682214                86.56 ns/op            0 B/op          0 allocs/op
BenchmarkBear_ParamWrite                 1412029               798.6 ns/op           456 B/op          5 allocs/op
BenchmarkBeego_ParamWrite                1000000              1159 ns/op             360 B/op          4 allocs/op
BenchmarkBone_ParamWrite                 1008853              1274 ns/op             688 B/op          5 allocs/op
BenchmarkChi_ParamWrite                  1717284               684.6 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_ParamWrite                 6536517               180.1 ns/op             8 B/op          1 allocs/op
BenchmarkGin_ParamWrite                  9557086               129.4 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_ParamWrite            540926              2365 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_ParamWrite           7386057               154.3 ns/op            32 B/op          1 allocs/op
BenchmarkAero_GithubStatic              27001914                46.12 ns/op            0 B/op          0 allocs/op
BenchmarkBear_GithubStatic               2568186               466.0 ns/op           120 B/op          3 allocs/op
BenchmarkBeego_GithubStatic               871456              1214 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GithubStatic                 82602             14210 ns/op            2880 B/op         60 allocs/op
BenchmarkChi_GithubStatic                1740193               671.4 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_GithubStatic              11515729               107.4 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GithubStatic               13017788                86.64 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_GithubStatic          225535              5136 ns/op             720 B/op          7 allocs/op
BenchmarkHttpRouter_GithubStatic        23060112                50.88 ns/op            0 B/op          0 allocs/op
BenchmarkAero_GithubParam               10224741               113.7 ns/op             0 B/op          0 allocs/op
BenchmarkBear_GithubParam                1145155               994.7 ns/op           496 B/op          5 allocs/op
BenchmarkBeego_GithubParam               1000000              1435 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GithubParam                 159064              7133 ns/op            1760 B/op         18 allocs/op
BenchmarkChi_GithubParam                 1277751               918.1 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_GithubParam                6307612               188.5 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GithubParam                 7861078               153.4 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_GithubParam           149268              7567 ns/op            1040 B/op          8 allocs/op
BenchmarkHttpRouter_GithubParam          3973720               292.9 ns/op            96 B/op          1 allocs/op
BenchmarkAero_GithubAll                    50080             23938 ns/op               0 B/op          0 allocs/op
BenchmarkBear_GithubAll                     4435            245079 ns/op           86448 B/op        943 allocs/op
BenchmarkBeego_GithubAll                    4156            341308 ns/op           71457 B/op        609 allocs/op
BenchmarkBone_GithubAll                      381           3296504 ns/op          698784 B/op       8453 allocs/op
BenchmarkChi_GithubAll                      5665            195096 ns/op           61713 B/op        406 allocs/op
BenchmarkEcho_GithubAll                    30034             39181 ns/op               0 B/op          0 allocs/op
BenchmarkGin_GithubAll                     35636             33399 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_GithubAll                289           4005054 ns/op          199684 B/op       1588 allocs/op
BenchmarkHttpRouter_GithubAll              21925             52235 ns/op           13792 B/op        167 allocs/op
BenchmarkAero_GPlusStatic               33204158                36.75 ns/op            0 B/op          0 allocs/op
BenchmarkBear_GPlusStatic                3235408               381.7 ns/op           104 B/op          3 allocs/op
BenchmarkBeego_GPlusStatic               1000000              1068 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GPlusStatic                5668977               203.0 ns/op            32 B/op          1 allocs/op
BenchmarkChi_GPlusStatic                 1762268               628.2 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_GPlusStatic               15786621                75.18 ns/op            0 B/op          0 allocs/op
BenchmarkGin_GPlusStatic                18751574                65.37 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlusStatic           896672              1335 ns/op             720 B/op          7 allocs/op
BenchmarkHttpRouter_GPlusStatic         43483508                27.26 ns/op            0 B/op          0 allocs/op
BenchmarkAero_GPlusParam                16314045                71.32 ns/op            0 B/op          0 allocs/op
BenchmarkBear_GPlusParam                 1350566               884.3 ns/op           472 B/op          5 allocs/op
BenchmarkBeego_GPlusParam                1000000              1344 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GPlusParam                  942118              1279 ns/op             688 B/op          5 allocs/op
BenchmarkChi_GPlusParam                  1632056               734.8 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_GPlusParam                11531385               101.4 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GPlusParam                 11728155               102.4 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlusParam            423982              2789 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_GPlusParam           6336380               176.3 ns/op            64 B/op          1 allocs/op
BenchmarkAero_GPlus2Params              11085147               106.6 ns/op             0 B/op          0 allocs/op
BenchmarkBear_GPlus2Params               1222870               991.3 ns/op           496 B/op          5 allocs/op
BenchmarkBeego_GPlus2Params               664377              1638 ns/op             352 B/op          3 allocs/op
BenchmarkBone_GPlus2Params                292208              3448 ns/op            1040 B/op          9 allocs/op
BenchmarkChi_GPlus2Params                1454524               793.0 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_GPlus2Params               8144325               141.0 ns/op             0 B/op          0 allocs/op
BenchmarkGin_GPlus2Params                9912289               120.4 ns/op             0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlus2Params          209048              5413 ns/op            1040 B/op          8 allocs/op
BenchmarkHttpRouter_GPlus2Params         5749315               197.0 ns/op            64 B/op          1 allocs/op
BenchmarkAero_GPlusAll                   1000000              1051 ns/op               0 B/op          0 allocs/op
BenchmarkBear_GPlusAll                     97982             10628 ns/op            5488 B/op         61 allocs/op
BenchmarkBeego_GPlusAll                    67842             16193 ns/op            4576 B/op         39 allocs/op
BenchmarkBone_GPlusAll                     42013             28946 ns/op           10336 B/op         98 allocs/op
BenchmarkChi_GPlusAll                     109096              9953 ns/op            3952 B/op         26 allocs/op
BenchmarkEcho_GPlusAll                    724444              1579 ns/op               0 B/op          0 allocs/op
BenchmarkGin_GPlusAll                     894699              1333 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_GPlusAll               29425             44770 ns/op           12784 B/op        102 allocs/op
BenchmarkHttpRouter_GPlusAll              421209              2533 ns/op             640 B/op         11 allocs/op
BenchmarkAero_ParseStatic               27619971                42.10 ns/op            0 B/op          0 allocs/op
BenchmarkBear_ParseStatic                2658307               433.8 ns/op           120 B/op          3 allocs/op
BenchmarkBeego_ParseStatic               1000000              1073 ns/op             352 B/op          3 allocs/op
BenchmarkBone_ParseStatic                1821030               703.2 ns/op           144 B/op          3 allocs/op
BenchmarkChi_ParseStatic                 1893363               606.4 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_ParseStatic               15557308                75.90 ns/op            0 B/op          0 allocs/op
BenchmarkGin_ParseStatic                19314535                61.85 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_ParseStatic           737965              1656 ns/op             720 B/op          7 allocs/op
BenchmarkHttpRouter_ParseStatic         44508679                27.20 ns/op            0 B/op          0 allocs/op
BenchmarkAero_ParseParam                20273876                62.57 ns/op            0 B/op          0 allocs/op
BenchmarkBear_ParseParam                 1543344               844.5 ns/op           467 B/op          5 allocs/op
BenchmarkBeego_ParseParam                1000000              1231 ns/op             352 B/op          3 allocs/op
BenchmarkBone_ParseParam                  816604              1606 ns/op             768 B/op          6 allocs/op
BenchmarkChi_ParseParam                  1689764               717.9 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_ParseParam                13302861                93.46 ns/op            0 B/op          0 allocs/op
BenchmarkGin_ParseParam                 15681054                76.91 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_ParseParam            576883              2090 ns/op            1024 B/op          8 allocs/op
BenchmarkHttpRouter_ParseParam           7237630               153.8 ns/op            64 B/op          1 allocs/op
BenchmarkAero_Parse2Params              15428432                77.79 ns/op            0 B/op          0 allocs/op
BenchmarkBear_Parse2Params               1128230              1011 ns/op             496 B/op          5 allocs/op
BenchmarkBeego_Parse2Params              1000000              1338 ns/op             352 B/op          3 allocs/op
BenchmarkBone_Parse2Params                721389              1423 ns/op             720 B/op          5 allocs/op
BenchmarkChi_Parse2Params                1538762               762.2 ns/op           304 B/op          2 allocs/op
BenchmarkEcho_Parse2Params              10273712               111.9 ns/op             0 B/op          0 allocs/op
BenchmarkGin_Parse2Params               12754458                97.04 ns/op            0 B/op          0 allocs/op
BenchmarkGorillaMux_Parse2Params          478572              2450 ns/op            1040 B/op          8 allocs/op
BenchmarkHttpRouter_Parse2Params         6373353               177.9 ns/op            64 B/op          1 allocs/op
BenchmarkAero_ParseAll                    685647              1759 ns/op               0 B/op          0 allocs/op
BenchmarkBear_ParseAll                     57692             20406 ns/op            8920 B/op        110 allocs/op
BenchmarkBeego_ParseAll                    34591             34004 ns/op            9152 B/op         78 allocs/op
BenchmarkBone_ParseAll                     33118             35524 ns/op           14160 B/op        131 allocs/op
BenchmarkChi_ParseAll                      59413             19391 ns/op            7904 B/op         52 allocs/op
BenchmarkEcho_ParseAll                    397791              3047 ns/op               0 B/op          0 allocs/op
BenchmarkGin_ParseAll                     502231              2420 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_ParseAll               14450             88260 ns/op           23632 B/op        198 allocs/op
BenchmarkHttpRouter_ParseAll              330852              3302 ns/op             640 B/op         16 allocs/op
BenchmarkAero_StaticAll                   122910             10197 ns/op               0 B/op          0 allocs/op
BenchmarkBeego_StaticAll                    5748            208661 ns/op           55264 B/op        471 allocs/op
BenchmarkBear_StaticAll                    14973             80023 ns/op           19960 B/op        469 allocs/op
BenchmarkBone_StaticAll                    21433             56290 ns/op               0 B/op          0 allocs/op
BenchmarkChi_StaticAll                     10069            114006 ns/op           47728 B/op        314 allocs/op
BenchmarkEcho_StaticAll                    48318             23956 ns/op               0 B/op          0 allocs/op
BenchmarkGin_StaticAll                     62385             21050 ns/op               0 B/op          0 allocs/op
BenchmarkGorillaMux_StaticAll               1165            973933 ns/op          113042 B/op       1099 allocs/op
BenchmarkHttpRouter_StaticAll              83532             13977 ns/op               0 B/op          0 allocs/op
PASS
ok      github.com/julienschmidt/go-http-routing-benchmark      225.839s
```
