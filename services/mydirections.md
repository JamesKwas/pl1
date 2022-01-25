# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?waypoints=place_id:ChIJ1T-EnwNwcVMROrZStrE7bSY%7Cplace_id:ChIJH5Vz0iRvelMRX-iZhLupIYQ&avoid=tolls&alternative=true&origin=Regina&destination=Fernie&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ6z2l-0AeHFMRsVR7t5YySjU",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ1T-EnwNwcVMROrZStrE7bSY",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJH5Vz0iRvelMRX-iZhLupIYQ",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJL_o8u45rZVMRZ6F5TZRpyO0",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 51.2636112,
               "lng" : -104.6188645
            },
            "southwest" : {
               "lat" : 49.2903844,
               "lng" : -116.1545229
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "758 km",
                  "value" : 758016
               },
               "duration" : {
                  "text" : "7 hours 26 mins",
                  "value" : 26753
               },
               "end_address" : "Calgary, AB, Canada",
               "end_location" : {
                  "lat" : 51.0448403,
                  "lng" : -114.0718702
               },
               "start_address" : "Regina, SK, Canada",
               "start_location" : {
                  "lat" : 50.4452112,
                  "lng" : -104.6188645
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "35 m",
                        "value" : 35
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 50.4455262,
                        "lng" : -104.6188635
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e toward \u003cb\u003e13th Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qq{rHzjp}R_A?"
                     },
                     "start_location" : {
                        "lat" : 50.4452112,
                        "lng" : -104.6188645
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1688
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 236
                     },
                     "end_location" : {
                        "lat" : 50.4455082,
                        "lng" : -104.6426953
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003e13th Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qs{rHzjp}R?tC?nCAxC@jC?hC@zC?dC@lC?F?jC?nC?jCAtC?jCAtC@hC?zC?dC@vC@dC?jC?rC?nCAzCAbC@xC?T?pB?zC?dC?xC@fB@tBAjC?jCAbA"
                     },
                     "start_location" : {
                        "lat" : 50.4455262,
                        "lng" : -104.6188635
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "33 m",
                        "value" : 33
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 50.4454919,
                        "lng" : -104.6431677
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003e13th Ave\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ms{rHz_u}RB|A"
                     },
                     "start_location" : {
                        "lat" : 50.4455082,
                        "lng" : -104.6426953
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.0 km",
                        "value" : 5023
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 344
                     },
                     "end_location" : {
                        "lat" : 50.4007981,
                        "lng" : -104.6440789
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLewvan Dr S\u003c/b\u003e (signs for \u003cb\u003eLewvan Drive S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAir port\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "is{rHxbu}R?f@hBRlBR`@DVDf@FzFl@lBR~APnALnBRhCXt@HD?x@HvGj@^DxCT~ADlB@^@XAx@CnBGd@CrAMNCfCWj@KTEt@MxAWpA]b@KjA[rCw@nA[HCf@OzHuB~EqAhAWpAWd@IdBUj@GtAOzBOdBE~BAf@?xBB~BN~BRdANfAP|BZb@FxB\\\\Fl@HF@zBVx@NxDz@`@FpBXtAR~@LrARbC\\L@jAPpANdAJ|@F^BpAFz@Bh@@h@?V?T?~C@nBAvB?t@?nB@nCAbA@j@Ax@?b@?X?P?nA@dAAF?`AAN@L?p@?tC@l@?T@nD@fCBj@?n@BtCKD?xA?"
                     },
                     "start_location" : {
                        "lat" : 50.4454919,
                        "lng" : -104.6431677
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 711
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 34
                     },
                     "end_location" : {
                        "lat" : 50.3968668,
                        "lng" : -104.6502055
                     },
                     "html_instructions" : "Take the \u003cb\u003eSaskatchewan 1 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Highway W\u003c/b\u003e ramp to \u003cb\u003eMoose Jaw\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "_|rrHnhu}RNJ@@B?b@?j@?~ABp@H^H^H\\LXNXNXPRNVTZXRTZ`@`@l@Zh@\\v@`@dAPp@VbATjAHx@LlAFfABdABnA@bA@|AJ`A"
                     },
                     "start_location" : {
                        "lat" : 50.4007981,
                        "lng" : -104.6440789
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.1 km",
                        "value" : 5142
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 174
                     },
                     "end_location" : {
                        "lat" : 50.3972924,
                        "lng" : -104.7226896
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eRing Rd\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "mcrrHxnv}R?vG?xP?vT?f@?pRA`K?|B?xG@bQAd[?v@?x@?tg@?~E?pF@hK?dP?fw@?^?\\?V?tO?nG?zN?fL?hD?xC?vD?n@?tA?xA?p@?D?p@?F?nB?|DAbB?tAAzCEvBC|@OtDIpBKjBYlGOhDCr@C~BEtFBvFHlFH`C"
                     },
                     "start_location" : {
                        "lat" : 50.3968668,
                        "lng" : -104.6502055
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "54.0 km",
                        "value" : 53952
                     },
                     "duration" : {
                        "text" : "30 mins",
                        "value" : 1779
                     },
                     "end_location" : {
                        "lat" : 50.3953663,
                        "lng" : -105.4773703
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSaskatchewan's Hwy of Heroes\u003c/b\u003e",
                     "polyline" : {
                        "points" : "afrrHxsd~RNrDHnBHjB?@Dr@@V?^Bv@@t@?J@j@?v@@v@?dADh@LpBHpAA|KAl@@xKElDFrN?pK@bVFfA?`F?pI?x@?|C?rD?lO?tC?x@?fL?rAAzN@fd@?va@?hN?rF?@?nIApA@vA?nB?x@?zKAfM?vM?v@AluA?t\\CvI?|F?hK?``@?v@?~\\?pI?v@?xG?v@?xG?nY?`o@?fS@bM?|U?zN?dU?~S?jK?v@?hK?n`@?`}@?v[?|U?v@?bM?lY?bT?x@?xG?fD?pB?dD@rBCbQ?hG?P@~D?lS?bTAvg@@`[?ju@?v@AluAAneC?v@?v@?hD@j[?|\\?hD?v@?xe@@bX?zLAhb@Czd@@fAAdR@nD?lR?tW?za@@p\\@xe@@xe@A~G?fM?zYCdT@~fA?hb@?hS?xe@?v@AtW?jw@?zjA?b`@?zNArn@?fb@?v@Af[?v@?dL?zO?v@?pI?x@?lG?nk@@jB@vA@`ABhAB`ABr@Dl@Br@JtAFt@HbAHr@Jv@Jv@D^@BBRF^DTRjA|BbMzAhItEbWt@dERnAb@zCNjARfBJz@?DHt@D^Z`EXzELjC`@lIb@nI\\|GPpDLfCt@tOfApTHrCBpA?d@@L?`@?T?@Af@Aj@Al@Cb@?HC`@AJCTC\\G`@Ij@Ih@Kh@?@Kf@K`@YbAOf@O`@Sd@Sf@Yj@U`@UZCD_ApAkAdAsA~@k@\\y@h@{@n@m@f@e@^]\\MNOR]b@U^Yd@]r@Wh@Qb@Sl@Qh@IZMh@Mp@CLI`@If@In@Gn@Gz@I`ACv@?\\AZ?jBAhJ?b@?dC?tP?jY?fQ?TAbG?hD?T?tW?`@?T?zNArJ?pH?v@?xA?bS?pL?v@?v@?hDApI?pIAhK?hK?hA?nK?xA?xU?|@?v@BvW?~S?fFAlw@?v@?fT?lB?f[Av@?hK?fQ?nT?pg@?bb@?bT?tW@tW?x@?jR?tW?v@?|U?xO@p^?|t@?~T?~aA@hT?fb@?v@Bdy@?rI?zN?zU?|U?jR?pL?tW?v@?|U?|N@lL?jK?xG?hD?fD?bM?`F?hK@p`@?v@?rP?`F?v@?nB?`F?v@?~C?jF?x@AnBAzCBbH?vEAdC?bK?hE@hA?jA?jAAjF@vI?xC?fC?pG@lF?|A?fD?`FApB?~@?n@@dG?`C?dM@b@?Z?tA?nI?rB?R?rCAv@?R?xC@lI?lA?T?vG?vD?hD?R?~A@rH?rG?zD@N?R?~@DjCFfCJxCJlBPdDD`ATxCRfCLjAn@lFf@xEt@hG^vCRlBVtBn@|Fp@|FX`CNrANtAbBpN`A|G^fDR|BLdBFrAJfCBjB@dB?dB?f@GlBGdBGjAG|@C`@I`AIfAK`AEf@QdBADg@vEGt@WzBEf@It@AJGh@Gf@}@`JEXg@vE?@u@fHMrAWfCi@jEAFQ`B"
                     },
                     "start_location" : {
                        "lat" : 50.3972924,
                        "lng" : -104.7226896
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "595 km",
                        "value" : 594864
                     },
                     "duration" : {
                        "text" : "5 hours 36 mins",
                        "value" : 20140
                     },
                     "end_location" : {
                        "lat" : 50.863844,
                        "lng" : -113.0054361
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSK-1 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Alberta\u003c/div\u003e",
                     "polyline" : {
                        "points" : "azqrHp`xbSw@pHIx@{@bICXc@~DiBtQo@nGcAhJa@vCs@zDGXOp@I^GPm@rB_AfCi@jAe@`A[f@mAfB}@dAg@j@k@l@_DzCKJgAjA{AvA]\\wCtC_@\\]\\{AxAsFnF]\\uDrD_@ZyBvB]\\uEpE]\\]\\yPnPcIzHyGvGwAvA}FzFyAxAiApAkBfCoAxBy@zAq@|A{@|BIRe@zAkA|Ew@dE]vBIh@iBbN_BrLu@pFkC`ScKlv@OjAQjAUxAa@zCKt@Id@g@lDeBdLYjBa@vCOdASvA[~BWlBSfBCRAR[~CUfDQnCI|ACh@?LG`BARIzC?DCrAAZAl@AzB?rA?T?r@?lD?x@?N?f@A|K?~H?@?|K?|AArH@~C?dK?lCKtF@f^?b@?|J?x@?v@@v@?v@?bM@vL?vUAd[?v@?hb@AzN?jK?jR?x@An[@nY?v@?v@?v@?lR?v@?v@?x@?fD?hb@?n^?vM?zG?pG?jR?v@@dr@?v@@jR?x@@~\\Atu@?v@?pI?fkA?lp@?x@@bk@?~E?rg@@|K@n`@?`F?nB@bM?`o@@jK?v@?pIBnE@rG?fA?pB?~A?~BAvD?nDCdBEbCCfAMtDIhBMpBEp@?DWhDYdDe@hEM|@_@hCe@xCe@dCk@tCmB~IIZeCjLkDxOuHp]qB~I_@dB]`BaFdUOp@qId`@o@vCo@tCOr@_AhEeEjRo@vCo@|CY~A[xAOp@Mj@{@zDsAxFgErRqH|\\Op@sKlf@kFdVeA|EOp@q@vCoA|FoGxY_BnHOp@oA|FaAhEoGxYoGzY_BnHaIr^yAvGa@lBqCjMw@hCe@~AiCzI}AnEqAtDkB|Ei@xAc@bAm@vAM\\_@v@cAxBcAxB[r@yAbDs@~A_FpKcVth@_ApBoLjW_ApB{ElKoN|ZmTne@}AjDmAlCqBpE}AzDsApDaAfDSl@CJq@fCENc@hBWlAOr@EPo@|Ca@`Cq@fEs@pEm@hDkDpTcLrs@eBfKoAbIwCrQMt@w@zEQ`Ba@nDEf@UpCKpCC`CApB@zBD~CVzFFn@Fv@NzAl@bHFn@?D~A~PbAfMlAlNXbDtD~b@ZbDfElf@XbDbEte@|@~JdDp_@Ft@Fv@vD~b@XbD`CtXHv@r@fIz@~JvGxu@Fv@fMrxAtAbPHv@z@~Jz@~JxB|Vj@rGFt@b@zEFt@fBpS@Hh@fGdAvLDj@nAvNHt@`@zEb@`FtBlUV|CFv@`@zEf@zFnBzTHbAb@zEXdDfBnSFt@b@zEFt@r@hIFt@`BfRbAnMLdCHhCFzBH~L@^BpL?`]?bMAhb@?tW?pB?nc@A~s@?v@?tPAhU?vF?dT?pB?hD?nB?v@?lR?x@?v@AbM?`F?xgB?jy@@`d@?v@?`F?dT?tP?hb@?bMA|l@?v@?rRLrYl@r]BpBBv@FfD@v@z@pg@vAzz@xAnw@B`D@d@BtC?~A@~CA~FEdNGtP?v@IvWGrPQ|b@M`WCdGAdCIdTAv@Md]M~\\?v@?v@ErIAnB?x@CfD?x@C~EIdTI~TEbMGpUGhMAnBGtP?v@ChDEzNAnBAx@AfDApB?v@EjKAv@I|UErI?nBAv@CzG?v@AtDCxGAhDApBAnBOhb@AnB?@?v@Mf[C`FAfDErI?v@CjGKxRAxGAv@Odk@Av@AxGAv@A`F?x@?FAn@Oxe@ApB?BGdVInQ[fy@Av@CzGAfDApBEjKEpIC`FCtG?B?x@?fD?x@@hK?x@?pI?v@@zG?v@?jK@dT@nY?v@@ji@D`S?hD@pBD~\\DlR?`F@v@@rIDf[@xG@xGHze@?v@DnY@xG@`F?v@BlTFxEH`FDhDbAlt@HpLB`FDfHAxG?vF?ll@?|N?bM?hD?xG?`F?xe@?`VApP?x@?tC?PCnCIxCG|BYvFi@vHCRIt@It@aA|Jo@jGKx@It@o@dGc@dEa@bEGz@IdB?BCt@Cn@ErBCrB?@?nB?~@Br@DhBHdBH~ABZHt@?FZrCXnCNhALhA\\|CJbANzALjBJvBHzBLzGJ`FZpODvAb@xSHrDH~EVpNDpANrIJrI@lF?L?x@?rP?`F@zG?r@?|G@rIBzT?xA@bCClCIvAE~@MfBk@~DcB~JuBzLCXOnAYdDg@rG_@|Ee@pG_@|EMhBQpBs@jJIlAGt@Ex@MlBCd@ANKxDA~AC|AIzHKvFKxGMpIIhFGvEI`FGhDQhKEhDGfDMxH?pAA`FAfDAx@A`F?nBOnm@?|AAx@?fD?x@AhKCnYC~UAxG?v@?xGCzGC|G?fF@|N?rBFnX?ZDfOFbY?v@?bBBnF?v@BbI@fB?nAHvGB`ABv@DnB@j@ZtI@F~@nR|@xQDv@n@lMJvCL|CJtCDrANjEH|Dr@t^pBrcALxGXzNr@t^LxGPhILnHD|ADxAL|CL`CNnBZvD`@fE@FHr@X`CbA~GjAjGlDjRZfBfA`GNr@tAtHvE~VlB`KbDlQz@lFLv@@DTdB@HN`B|@~Jb@tERbCfAvLh@tGlA`OPlBr@fI~Dne@L~AXpGDzADxA@tAChBCjCGrBOlCIhAKtAs@lGwIvv@UjBIt@s@nGuAxLs@fGeC|TwJx{@iAzJIt@sFrf@i@vEIn@m@nFwBvR{@zHo@rFSjBs@lGKt@s@lGIt@}@dIwCvWCP_@`DsAnL_AbIq@lGwB|R_DvXYfC[vB_@hCQnAyA`Je@jCIb@g@zCsKfn@Mr@Mr@Mr@sJlj@{BtMMr@sHxb@[fBcAbGkBnKw@dFKr@G`@OfAKt@[`C_@~C_@~CYtCKfAi@~FK~@WxCGv@k@|GcChXIt@yAbPGt@a@hEaCjWWfDGt@?@UtDOzCIxC?HEdBEhBAhAG~E]dXMrIAv@Av@i@jc@c@r]]tWEhDSrPAv@[|UAx@QzNAv@EtCM|KClBAvA?`BDvBFtADbANzAJfABJHn@Jr@Lp@ZzA^xAd@vAL\\Tj@`@z@LXNZp@fAt@hAf@r@rBnCpAdBv@fArCxD`EpF`FvGZb@Z`@DFp@~@\\`@nBlCnBjCZ`@Zb@tAhBZ`@Zb@Zb@Z`@Zb@pEdGNP`MrPZ`@xIlLn@|@~@nAn@|@V\\BFXd@b@n@p@lAt@zAJTVj@JX|AbE|CxIHXTl@nAnD`ApCRl@`@fAzEnNz@|BbAtCrB~F^fAnAnDh@xAp@~An@xAh@hAt@|AdApB|@|ADDnAtBhAbBhBbCnCdD~CtD\\`@d@j@bExEh@l@NPnG`HpCxCl@n@LNdEpEvEjF\\^PP~BtCn@t@z@dAb@j@fCbDpCrDfC`D|DbFPTdAzAp@bAd@z@Xd@fAlBt@zANVv@dB\\r@^z@FNVl@z@zBZ|@d@vAd@tAj@hBv@~B|@pCTn@\\bAZz@f@lA~@~BbBpDrBhEtBrEVh@zBzE~DnIfGnM~AfDvExJ|F|LtBnEbDbHl@nA`BjD~DpIh@fAt@~AnCzFHNLXhA`CdDbHVh@vAvCVh@BFj@jAVh@n@tAbD`HBB~AfDVh@fA|B|DpIVh@vBpEVh@nFbLjHpObCdFDJfAxB|AhDVh@`@z@dCjFn@rAVh@~AfDXl@lCvFl@nAfAbC?@t@jBf@xA^lAb@~A\\|APx@P|@^|BVrBLnAF~@HdAH|AH|ABhABbA@`A@|B?|@?jF?|M?dF?|A@hDAzB?zK?v@AjI?tM?|C?fD?x@?lA?|O?bLAhE?pI?xG?lYAvX?vJ?nO?nB?x@?`E?nC?v@?tH?\\?fS?Z?x@?xG?bA?pU?Z?Z?|H?~C?xM?zM@fB@tBBvB?NBv@BbADbBBf@DrAH|APhDVzCHfALrATrBRdBNdAHt@@HTzAh@rDvA~IPjAd@xCPdAJr@ZpBT`BPnANpAHn@PlBLnAHdAHrAJjBRpED`BBtBBrB?jBAhCAhBE|AEdBMxE{@dZCv@QvGmB|q@]bMsBrt@K|CEtAG~@E`AG~@O`CKvAEb@Er@A@MzAMfAIt@CTMfAK|@Mz@ETE\\QhAk@jDe@fC[tAc@rBqAdFu@tCqFlSyAtFQn@Qn@oCfKcMfe@}BtIwEhQsMtf@Qr@u@nCyArFa@`B[vAOt@SfAObAKt@EZGb@CPK~@Gp@Gp@IbAGhAE`AGbAWxGE`AWvGMzCU`Gc@~J_@~JG|AEv@InBOxDUlFWdHiAbXeBdd@Ev@GjBObDOnFEjBClAArA?pBA|G?bB?`L?l@?v@?|B?tE?`F?dAAxZ?bM?v@?pI?v@?x@?tW?rP?pB?rP?xG?`A?bR?zCAtM@bZ?nK?x@?v@?tN?D?rP?x@?nF?tS?tA?Z?r@?B@bABfB@t@@NHbDJzCHfCXvHZhKBv@JpCDlA`@vLXrIHrBDr@H~AV~CBVPpBFp@NtAPhAl@bE^vB`AbFhBbI|D~O@FLj@`AtE`AjFnBvLh@|En@dGn@rI|AhUDv@b@rGFv@rBrZFv@b@rGFv@LlB\\|ELlBDv@v@zKHfAJt@L`AJr@t@xFv@bEr@zCJ`@n@bCDLbA`D`BpEzCrH`AdCnBzE~G`QVj@Tj@pD`JzCtHdChGTl@j@vAnB|Ej@vApD`JvApDVj@fEnKxJpVTj@lMx[BHbAbCl@vA`C|FDFVh@|DpIfA|BVj@~AfDVh@Vh@lC|FlInQrEtJxN`[~DpIVh@@BrAvCfApCTn@L\\z@vCh@xBj@xC`@fCTlBRtBDr@Fr@?@Dl@?HB`@D|@?N@d@Bx@@`A?xA?dA?pB?L?x@A`C?nE?v@?j@@vK?~B?f@?|H@fJ?xG?nB?lR?v@?rP?`F?jR?rP?x@?fD?v@?xG?tW?x@?pI?v@?v@?xG?x@?xG?nB?hD?v@?pI?hD?nB?hD?bM?jR?jR?rP?x@?xD?jK?|U?lY?v@?dT?nB?v@?pB?~E?dT?dw@AtW?v@?hK?xG?xG?zN?`F?v@?`F?xD?|M?fI?v@?fD?x@?~E?x@?rP?v@?pI?|U?v@?zN?pB?fE?hC@`Y@lF?v@@dN?T@hD?fD?t@?@BbH@dG?rD?`F?fD?hA@rDBtAB~AHjBH~B^xHN~DDt@Bv@Dv@R~EBv@f@tLNnDDhAVrGH~Ah@hMR~EDv@NfDBv@n@tNBv@r@lPDv@HnBBv@JlBXvGBv@Dv@^`JB\\HtBBv@VbGJfCJ`CT|F@XRxELrBFbALpBFd@PzANlAJj@Jr@?BP`ARdADNNp@l@bCf@rBPn@Np@@B`@|ANp@b@bBNn@T|@Ld@bAdENp@bB`HlBxHp@hC`BnGfCtJLh@jBbHl@zBj@vBlCvJf@lBzArFtB`IlBdHbAvDrAjFXjAVfAR|@R~@X|Aj@fDXhBb@zCHr@l@vE`A~Ht@bG@Fr@fGvAjLTrBt@bGJ|@Ht@f@xDBZJt@n@dFd@fEjAlJ`@jDnBbPh@jE~AtML`Aj@vEb@pDZnC~@pH|ArM`A|H~E~a@bCdSlAvJdFdb@Ht@bCdSvAjLJt@jAvJj@vEThBnB`PtBbQvBnQzEn`@lCtTv@|GbAfIl@bEj@jDl@~Cz@rEdBdHhA`EPn@pFzRbAnDBHn@xCl@tCNr@@Fn@pD|@bHVhCLvAP~CLbCDpAFrCDhDJdIv@tl@HpEH`DTtFDt@Dv@PvCR~Cx@nKnA|OPxBNlBXlDLbBFv@f@pGf@rGFf@h@~GFv@~@pL~AtSbFzn@RnBvBzSr@dFjCbQThALr@zJzh@hFzXNr@nI~c@|D|SLp@tBzKLr@lJfg@pBpLTpAdA`FjA|FNr@l@tChBhHb@dBv@hCf@|An@rB^fARn@bBhFRh@`ClGtArDj@xATl@lChHjAtCj@vATl@|ExL~I~TbHlQTj@vLzZp@bBjBrGLb@DJPn@xArFjAlG@FrA~Hh@rEFp@bAzJLtARvBx@tJRvB^|CbA`H|@bFLr@Ln@xBzIrAlFxCrLBPJ^DP`@`BfBfHHXxCtLH\\`@`BDPJ^v@`DpAfFfAjEb@fBPr@x@bDLf@hBpHPp@@Bb@dBdErPf@vB~@rDPp@`@`BtJj`@fAnEbAbENh@@F`@`BPn@Lh@Pp@Rv@Np@Pn@Lj@t@vC`@|A?BPp@Nn@r@pChChK|@lDt@rCd@vBf@pBPn@`@bBr@rCNp@Pp@t@lCVhALb@`BxGb@dBt@vCb@`BZnAr@rCJb@Nn@DNlA|EFVJ`@@@^zAr@rC`@`BPp@p@hCl@dCRx@@L@Lt@rCPn@b@`BPn@XfAd@~Ad@~Av@nCZbAbCpIf@jBlMhf@pDvNfAhEnCrKt@|Cf@jBh@~BBJBHPp@BLt@rClCvKn@|BJb@DNJ`@DNpBhIp@rCJ^Lf@HXf@dBp@dB|@vBN\\BFRb@BD?@|@zAdA~AtC~DJLlD`F@BfCnDzB~Cd@l@dArAh@p@Zb@FHf@p@v@jAd@v@R\\NZHRTh@\\~@^bAd@lBBFDZVjAVdBN~AJfAHhAFlA?L@t@@pABvJ@dA@pDBtGBpI?p@?|@J|Z@hD?v@FvP?rQBpB?v@HfIHrX@lDB|ENte@@ZDnQ@zABxJH`^B`MDvK?v@?hBBhF?L?f@@rA?vDAtA?JAXAjAC|AEbBG~AI|CCXEt@A\\Q~CSlCADGn@MtAEVWdC_@xCSpAKt@yAtJ[lBaBhKiEtXu@zEObAu@|E{ArJETYdBSvAOfAKt@?@QzAQ`BW~BKpAKjAIdAMpBI|AI`CIxBG`CEnBAtAAzB?nB?nD@rA?D?p@FlI@rBFpIHjR@v@FxN@v@FhKB`F@nB@nBJbTDpIFzM@zBD~HDzIFfDHxDJjCHrBJ|BLvBLrBV~CTvCT|B@HVfCThBBPPnANnAL|@XfB`AdGJr@hDhTXfBnAzHJr@Lr@hFj\\xCbRNr@P`Ah@hCn@tC`@bBLf@x@zCFRvA~EbAtC`AfC`BnEvB|FxDxI|@pBdDpHtInR|DxItHpPpBpE|AjDlKtUjC`GdA`Cj@tAVj@bA`CVl@nBvEHPrC~Gp@bBP^xAnDj@vA\\x@jDpITj@xAnDTj@nBzEdKzVfDfItE`LRd@bBfEz@tBf@nA\\|@`@fAl@`B`@jABH|@rCr@zB^vAz@zCj@zB|@|DZrAPz@rA`H`AnElCxMf@hCNr@Np@fCfMlA`GLp@Lh@~@rE|@jELp@bIj`@xFzXh@jCZ`B@BhChMLr@tEfUNp@FXdAbFLr@|@hENr@zBtKnAbG~AbIzApHJh@@FNp@xBvKlA|FLp@^dBjA|FlA~FhCfMDRH^bG~YNr@nI|a@lBbJlBhJj@pCNp@zArHrAvGNr@vEfULp@|@jENp@zApHNp@jA|FzBtKrHx^FZNp@jA|F\\dBlA|F|@jE\\dBhDlPzApHLp@|@jENp@fEtShCfMjBbJvEfUjA|FlA|FvD`RXtAtA|Gr@lDjB`Jh@hCnBpJVpApApGZzABHpAnGz@`ExAfHH^|DrRzDnRdCzLNp@\\dBDPtA|GPz@dAdFh@hCnBtJNp@hDnPp@bDh@jCzBtK~@vErBzJtE~Tr@lD|@hEXvAdA|ELl@Np@TfApApFj@zBPl@bAvDf@hBhA~DZfAnDjMl@tBNn@Xz@l@|B|CtKbApDp@`CdCtIbApDvBxHv@nC\\pAnAlE^rArAtEvAfF@@Pl@v@nCPn@Pl@v@pCPn@\\lAjAbEfA~Dz@xCrAxEDJPn@vBtHZjARn@fA|DRp@vGpUPp@d@|AzAnFPn@|ApFr@hCTt@lCnJDNPn@|ApFv@nC~@dD`AhD@DNh@Pp@x@tC|@~CPn@Tx@~@~CfA~Dp@zBn@zBdA~Cj@dBd@nAl@|ARf@Td@`@`An@vATh@tBjE@DnDpH`DtGVh@`BhDTd@`ElIVf@JVrDtHVh@p@pAP`@DFVh@|@hBbAvBr@vAvHzOHPVf@Vh@Vh@rEnJBFXf@vBpEtBhEVh@x@`Bd@bAp@rAVh@`ArBlAdCv@|A~DfIj@jAfAzBVf@`BfDBDR`@~AfDn@rA~AdDnLnVbBfDfAxBVh@fBtDxFfLFNVh@JT|@jBz@jBl@pA`@bAVn@n@`BhA`Df@xAjE`NtDdLhAlDRn@lDxKrHnUb@rAPj@@BtBvGdA`D~HnVlGrRTn@d@vAd@bBjA~DrCpJtAhG|BjMj@tEzBjQRzApCdUjArJj@tEHt@v@jGlCvTxBhQHt@j@tEJt@^~C~Gjj@Jt@Ht@bB~M`@~C^~CJt@v@hGHt@v@jGHr@xAjLfAxI|QzzAHt@v@hGVxBPzA^fDVzCB^V~DXfG`ApV\\lIBv@D|@zBvm@b@|LP~ELdDZlIt@zSVtGLxCV~Fr@bRBv@P|EDv@ZlIBv@d@zLdAbYP|Er@bR^rJXlIFnBDt@d@tNb@|LXtIDn@Bv@d@bKlAnWjAdNd@bEf@fDZlBLp@RjAdB|J`Mnq@rA|GbAbFtAfG|BjIjArDhCfHh@xAvArDzGbQ~@dCvApDjA~C`ClG`CjGTl@jB~ETj@`@fAlCzGDNnAbDbLbZnHpRdI|STl@jHdRxDdJb@`AJRxDzH|ArCh@|@dBtCxElHt@jAZb@l@~@dFvGdZr_@zGtIjInKHJzGzI`BpC~@dB\\z@Zr@zAlE\\hAb@xAnB~INp@tCrMtE~SH^Np@j@hC`CvKt@rDh@~BfAbFjAtF`BvHhBhIpBpJ^hBx@bE\\lBLr@^vB~BxNhJtj@|AjJLr@Jr@t@nELr@Lr@`AbGLr@Jr@zDxULr@lBnLrBbMpEpXzExYfAzGnAzHXfBl@~Cd@dCR~@Nn@ZvAd@lBvAdF`@lA^fApAlDzDbK~BbGxAzDpBdFZ|@xBxFjD`J`AjCRj@?@Rn@Rl@Rj@fAvDRx@Pp@Tz@pAlFpAhFdAjEr@vCb@jBn@jCv@bDJ`@nAfFnAdFz@rDJb@zAjG^zANn@Pp@hDlN@@~A|GvAhGn@xCf@lCn@nD^jC`@tCJbAJt@BXXrCRvCFr@VpDLhDBh@Bv@FrBLdMAd^?v@A~L?xL?vUAnI?fKAxfA?|W?pR?v@?n^?v@?fK?v@Axc@?fK?nW?pP?nPAnI?nW?vNApI?v@?nW?fD?vG?v@?rC?vP?vN?v@?nI?fD?xU?v@A~E?~E?fK?vG?fR?x@?hI?|@@nI?~a@?nI?~E?xN?v@?~L?fD?vU?v@?fD?v@?vG?jO?vG?v@?pI?v@?~E?nB?fK?v@?xq@?~Z?zN?v@?hY?v@?v@?paA?~Z@ni@?~E?`p@?v@?vG?~E?fK?~L@hK@nP?nI?jCBxCBh@BpAPvEhAxTt@tNt@pNDt@p@rMl@bLhCvf@Dv@~@rQFxBBv@LhE?lA@v@?lA?nCAx@?v@AnAOtHQnISdKa@hSOlGOlICv@sAzo@K~ECnBOtGGfDQnI]lPCv@_@dR_Anf@IrDAzCBdDHnDBl@PdDPjBJpAZbCDb@l@rDJl@^fBNn@XpAl@tBjAhDlBtEfH`OtBnE~DnIfGjMVf@vExJVh@tEvJVh@lAfCfE~IvBfF?@n@dBv@|BTn@FTv@bCdAnD@BZlAz@rDhA`FPz@jArGpAhHHb@|@fFvApIxAlIfElV\\tBf@vC^xBp@`Et@jEJh@b@hC^pBR`ALv@V|A\\pBrEzWvCvPBPnAbHBNb@lCLv@b@bDb@tDJ`A@HFt@JbALfBHpAHlADx@H|AD`B?VFbBBtA@vA@tB@v@@zABjH?R?b@?`D?dT?xH?~b@?VAdGAnI?fK?nI?v@?vo@@tE?fD?nBBv\\@~S@~HHxCJbCR~DRdD\\lD\\xCPpAJt@@HV`B`@~Bz@nE`@zB`@|Bx@lEvAxHzBvLdLbn@|CrPnC`OnC~NzDzStBfLVtATvAfJbg@tArHNp@tArHLr@vE`WdBdJLr@vJth@bBdJLr@p@pDRnALr@RhAn@pEj@lE`@dDNtAHt@Fh@b@dF`@vEXbDLpAx@~J~Ch`@x@tJDh@@LXlC\\`Dx@fGl@lDJr@pAvH|BnJfHfVnEdOv@nCtIvYPn@fLd`@tEtObEfNf@hBfAvD`BnG`A|D|@dEj@vCP`ALr@@FdAlG`BlK~BjOdB`LfFl\\Jr@dBbL~DnWLr@Jr@Jr@rBvMJr@xAlJLr@jEdYfB`LJr@bK~o@~AfKl@`EXtBb@~D@HTdCP|BH`APlCLxCJfCD|BHnH@lW@nC?lAFhiA?pN?vG?tGAvq@?v@?~L?v@?fK?v@?dg@?v@?fR?v@?nPCtG@fQ?V?^?~L?~I?~O@fRAbN?rW?vG@pU@lLBhH?v@B~GF~CL|EFhD`@nJd@bHnBjTFt@tGns@Ft@pAfN`@xE~Ehi@j@~FnChZHt@~LtsAFt@l@lGt@dIr@xHnAfNFt@j@nGHt@|@xJdClXfApLFt@PjBjBhSXbDHt@dApLl@lGdClXPjBPjBFt@bEbd@n@xGj@nGnAfNnEbf@fApLHt@j@lGZ`DFt@l@nGX`DRjBt@dIFt@b@vE~@zJFt@z@fJJfAtB~TfApL`@dETbCDn@F|@fD|^`AtK`BxQBTrCxZ?BTdD\\lFN|CHzCBfA@~A@v@DdD?B?r@?~E?fD?v@?~SAnIAdY?pL?d@?d[?~EA|a@?lQ?v@?tc@?v@AbI?zB?nL?fR?tc@Av\\?v@?dK?nB?v@?nI?dg@?v@?pA@|F@nB@zH?dP?lvA?v@?bt@?~E?vG?nBAfK?dYAne@AtG?rQAzC@`M?nC@jP@fE?~F?bCA|BEjDAx@KnIItGK~IItHExDAjDChG?@?t@?`JAtQ?~E?hH?nBAfD?dB?hF?v@?dD?v@?f@BnIDhGJhFF`CDlAJtBLtBf@~HTfCFt@?@PhBN~An@xGtAdNv@bIhEfc@Ht@dElb@v@bIPjBd@vEHt@PjBtC~YHt@rA|MrEhf@Fl@LnBTxDLzBDlAB`@JzD?BBr@DbBDbCBdB@bB@|BAzC@pJAdL?zEAxQ?`CAt`@?v@?v@?dY?fB?v@?fRAtN?vG?fD?nWC|S?v@AjXAp]?~S?v@?|S?v@?|P?`F?v@?~S?vN?v@@tq@?jBChg@Ctw@?fD?fD?nB?nB?t@?v@?~L?v@A|o@Gzo@EdYCjI?z@@`LCfD@dE?BDnFD|BFjAD|@HhA@ZNnBHbALlAPxAJ`AT|ATxABJn@tDbAzEpB|INp@n@tCNp@Np@Np@Np@~BnKLh@@F`AfENp@Np@Jb@BLNp@Np@jB`Jx@xDd@tBd@rBLp@Np@Nr@h@|BDV~@fENp@Np@^bB^bBNp@pB|IrBfJp@~C~@fEnEfSn@xCn@tC~CtNNp@nDdPhAbF|AhHFXh@bCTbAVnA^tB\\rBT|A?DJr@DVPxAVtBRjBNbBNvBNzBBh@NpCD~@DbBF~ABpABjB@pB@tA?~D@jA?`S?nG?zo@?nB@fK?fRA~S?vN?dC?hL?v@@tc@?v@?dK?~Z?dJ?nB?|a@?nB?nI?fD?vG?nB@lW?v@?vG?~E?nB?lP?v@?fK?~E?nD?vN?~L?v@?dK?nW?lI?nI?v@@l^AfR?v@?t@?xI?l@?nB?dO?fU?v@?fK?nB?v@?bA?hDAzA?DAt@C`DAtAA^ChBC|@Az@MxEGlBCl@?HMdDUvEQjDKzBQ~C[rGI|AEv@UzEEv@ALOtCStDMtCSrDq@`Nm@xLc@pIOdDQdDCt@KnBQbDCv@KlB[rGQdDIlBEv@QdDKlBIlBEv@Ev@g@vJMvDS|FExCE~F?~C?~C@rBF|CDlBH~APlDRhD@N\\hE?Hp@zHbAxJBLFt@\\`D@Fj@dGl@lGHt@VnCT|BPjBHt@v@bIHt@Ft@v@bIZ`DRjBv@bIhAnL~BdV@NFt@l@lG?Dd@~FH`ALfBNlCLhCDt@?@FhBLxDFxB@\\@x@BdC@bDAjE?dD?rAWvSI`GAv@YdVGhCIpFKxIGrEO~MGhEEtCIpHIbGEhFSjPAv@UdRw@lq@AtI?v@AfDCpK?lN?hJAv@?zE?B?tGAdD@`T?nB?v@ArMAhK?pJ?t@?~E?v@@RAxOG`}B?`O?dDB~EJ`EFjBF`BRvCPxBVjC`@zCVhBNdAh@zCd@tBVjARx@Rt@L`@Pn@@DZbAdA|CPh@zAbElG~Pl@zA~BdG`@bAbEvKp@hBZv@@B\\|@d@pAn@fBhAxCb@jAj@`B^`ATp@DHJXTn@Tn@Pf@Tp@V~@Pl@J^Nl@Np@J^Nn@Np@Jh@d@zBNr@Z|AZbBd@~BNp@`A~EvAfHb@zBnMto@l@vCvAfHdBvI~@tELp@|DzRr@nDXzA^fB`@tBb@tB\\fB`BfILl@ZxAd@dC`@nB|CtOnBrJnAjGlBpJXtALr@BHVpARdARhAPhALz@Fb@D^DZ?@Dd@@LD^Dh@Dd@Bd@@LB^Bl@Dn@B~@Bf@@d@@n@?x@@n@?T?LAlA?RAfCAvAAv@C|CA`A?v@AjBCpBG~GA`AA`CAjA?ZAfAAlBCbB?VAr@?BAfCAhBCtBArA?B?t@Az@AvBCvBC`CAfBA~@A|AArBCfDAtBEzD?jACrC?ZAfBCjCCtCCdDAt@?r@?BCjC?ZC`CA|AAbAC~CCvEE~EA`CElE?h@IxKAfBCbDCbEGfHExF?l@CzDCnCCfCAtBAlBClCAvAAnA?ZArAAhBG`HE|ECrDA~A?`@?TAr@AbCC|A?XCdEEfECbCCvD?h@CbDE~FCbEEjGEpFCvDCrDE`E?b@Ax@AxBEnFAtBAdB?`B@~ABfBBt@Dz@RzEXlH?BJlCJdCPtEPtEVlGP`ERbFHdCNtD^zIv@lSFdBDt@Bv@PnEFpATxFBz@Bp@TnFHbCJlCFzAFrBDv@JtCNjDNlDLhDJ~B@b@NjDJ~CLdDBv@HlBP|EF~AZlJRvF@`B?vA?vACxAEfBG|AAVCj@IdAY~CM`AMnAUvBQ~AsF~e@oClVKr@qBlQ]~CoFle@iDvZk@`FmGlj@UjBgAtJsCzVeCnToCdVKt@kHlo@mDf[_@~Cw@bHOrAAJKdAEn@KvAABOdCQbD_@bH{Dvt@Et@gBh\\Et@QdD]rGEt@Ev@Et@Ev@}@dP]rG]rGE|@y@xOEt@c@jIKlBEt@gAtS]rGg@rJUjEeAbSmAlUStDUpEYbFcAzRARkAnTEt@gAtSUvEcD`p@EjAE`BExBCnC?p@AdA?|@BnC@z@@z@@jALvFNbGPpHNzFDvBHzCNxGNbGFjDDvCBp@`@tPLjFD`BJhE@VRlJBv@FzBB~A?@NvFFrCTxJJ~EBbADjA@b@DpBHlDBl@DdBFrC@Z@l@L~EBhAXbLFtCFnC@jCAdBA|AGbCMnCEd@Ep@MxAWlCUhBUvAMr@WrA[rA_@vAm@rBc@vAa@lA_@jAgAbD_ClHgAfD{AtE{@jCsD`LeIvVc@rASl@qAxDwRnl@iI`W_Nza@Sl@}@lCqHnU{BzGqG|RgBvF{@~Cs@pCc@|BSdAUnAStAaDjTCRm@|DKt@sEzZiVjaBw@nF[lBSpAg@xDc@xDo@vHYvEOrCO|DMjGClBAfBAbDBjL@|H?v@BfK@jHDx]BtE?dHD|XBjBBvADlBL~CFdBh@zJRtDdAbSlA~Tl@~Kd@tI\\`G\\dHBZZ~Ft@zNf@nJV~Ef@nJFdARpD\\tGNnC^dH`@`If@lJRnDDt@XpF`@`I\\vGV`ELfC^jHVfFZpFf@pJZlGDt@H|A~@vPt@nNJnBDt@ZvFRrDv@jO^`H@^f@fJf@bJ@N`@xHTxD`@`IBj@TfEPpDNpCDdA@^?X@`@?d@@n@?b@?p@?hQ?jE?rL?xL?rD?dPAjO?bB@nH?vA?v@?b@A`G?`B@n^?`B?bG@lCAtN?bE?jJ?~L?pC?b@?jG?nB?bB@d@?bA?d@@b@@hABbABt@FxBHdBHdBHhAFfAJdAHbAHv@RdBNvAPvALx@bAvGHb@hAdHrAvIh@dD|@xF`@hCj@pDJr@p@dEx@jFZrBh@fDv@~Et@xEz@tFLr@XfBnAdIVdBZnBp@fEZpBDV^`Cv@xE`@nCz@hF|@zFZ|BTnBPdBHnADt@D~@@JBv@?BBzA?hEIvCCh@Ch@Ev@KlAO`BM`A]zB[zAKh@Mj@W~@Qp@i@fB[x@i@nASb@a@x@U`@[j@_@l@ILQTi@r@OTY\\MNONeBpBON[^wA~A[\\aAhAkAtAEFiCtCkCvCwAzA_BdBs@v@u@t@g@h@{B`CON]^STs@v@e@n@e@l@CD_@h@k@z@g@x@k@~@GFS\\U`@w@lA[d@}@vAQXyDbGeA`B}AbCqArBo@bAiAbB]h@gDbFo@bA[b@kAdB{@rAy@pAuArBOVSVsB~CkAfBkAdBaBdC]h@[d@mBzCU^{@vA{@pAqAtBsBdDk@|@INgAfBiBvCYd@gAfBsArBa@n@uAvBwAvBuBdDy@pAq@bAy@pAoAnB_D~Ee@t@mEtGORuBbDaBdCINi@|@k@fA}@nBUh@Q`@uAfDaAdD]tAi@nB_@jBABQz@]bBkA|FOp@Or@UbAUdAAJCJSbAU`A}@hEaDhOeDrOMn@y@jEI`@g@dCSrAMn@SrAIh@Gb@MhA]fDSlBG|@{@jNOjCGz@Ed@KfAU`COrAKr@Kt@AFUzA]hBS~@Q~@Md@UbAc@zAOh@ITEL_@pA]dAUp@Sf@MZGNi@lACFKRwIzPs@|AsA~Cy@xBw@zB{@vCq@~BI\\Mb@Md@kBjIo@nC}@~DYfA[xAQp@}@~Di@jBYhAGPo@dCs@|Bq@rBqAlD}AxDGNaBhDq@pAuBjDYf@A@m@dA}@hAe@n@q@z@MNSTc@j@oArAwB|Bq@t@g@f@{@|@wA|AyA|A{@|@]\\s@t@GHwA|A]^wB|ByA|Aa@b@sAxAg@h@GFyDfEcElEsDrD}@~@QN[\\}BbCs@v@c@f@o@r@i@j@s@t@A@A@UX}@bAyA|Ay@x@ONa@b@{A`BuCzCa@b@u@x@]^]\\WXED]^yA|AuA|AKJy@|@{@~@oEtEwA|AWXcBnBqAxAy@`Ak@p@gApA[`@kAtAg@j@iDxDGFoApAABcAdAw@z@]\\sBxBYZYXe@f@YZ{@z@EF[XuB|B[ZA@c@f@UT[\\A@]^sCzC]^]^qE~Ec@b@WXIHMPq@t@m@r@GJQR]f@o@hAc@x@Q`@y@fBKTEJYn@e@dAm@pA]x@}AlD[t@[t@yC~GuA`DCHeA`CiBhEGLmDhIu@fBgAdCSd@oBrE}AvDqBtEUh@sDpIWj@qBvE_AvBm@tASd@g@jAc@bA]z@i@hAe@z@_@p@e@n@e@n@e@d@e@f@i@b@YREDYPIFWNWJc@TC@a@Lq@Tq@N[DI@}@NmAJA?}AHgAFO@_BFo@Bq@Do@DgBJk@BeAFE@O@S@C@WBUBWBUDWDWDg@L_@LWHc@P]PSJQHGDUNi@\\]Xa@ZSRA@QPSTQRSTQVSXa@j@QVe@z@]t@Uh@O\\Wn@IVQb@m@dB}@lCKVuA`EUn@}@jC{@dCELoApDIP{AlEWt@g@pAO`@}AjEYv@[|@mB`GqAxDiAdDmAjDy@`CuA`Ee@pAw@~BYv@a@lAA@qBpF{ApEa@nAuA`Ee@tA_@bAWv@qC~HSl@iBhF[`AUl@Wx@q@jBYz@CH]~@mErMy@|BYx@y@`CkBpFg@xAyB|GCHkAlDyAtE_AvCCFiAjDo@pB}BvHwBvGcBfFQh@gAfD]dAUv@{ArEyApEu@`CITu@|B[~@[z@[x@]|@a@dAy@nB]|@eAdC_@|@o@|A_@|@]z@]z@o@bBYr@M`@c@nAm@lBOd@e@xAA@i@dB_@hAq@pBi@dBiAjDiDnKgGjRqD|K}CrJSn@{@nCQh@mFlPwBzGSl@oAzDoAzDyDnLY|@kApDq@tBSn@CFgC|HCJkAnDQl@y@fCgDhKoDzKyDtLcCtHu@|BqA`ESl@]dAsBlGqBjGs@xB_BdFe@rAmAvDa@nAc@vASj@aAzCaAzC_FjOsAfEwFbQqCtISl@kB~F_Mz_@sC|IoB`Ge@|AkCdIwBxGIVcA`DqA|Do@pBcBjFcI|Va@hAg@zAqAvDmJ`YeBfFsRtk@gCrHgAbDwDbLSn@i@zA{@hCmJ`Y_KpZeIbVyNfc@iCvHeBjF}GfScBfFSl@qAxDsFjPeBfFwBtGUl@aSxl@a@lAoB`G_AnCSn@Sl@yBtGsBdG}DnL{@jCeBdFi@~AoGjR{ArEyBtGaAvCM`@mDnKM`@_CzHu@jCSt@Qp@i@tB}@rDu@lDc@jBMl@o@xCo@~CaBvH{AdHc@pBeFhV]bBq@~CyEbUyCpN{BtKcCjLgBhIOv@c@tBYtAKf@m@|C{BpLMp@UjAq@tDMr@Oz@g@rCi@~CcA`Gg@vCO|@s@dEmHtb@wAjIMr@iFpZW~Am@fDm@jDkEjWu@nE{BrMeFrZgKrm@O`Am@nDo@tD{@bFiDbSeCxNGd@cDdRiAxG[fBuCvP_FxYuBzLc@fCm@tDo@nDgFrZMr@AFsCzPyChQc@hCaDdR]pBcAbGi@|Cu@jEMr@e@lC[dBk@zCe@~Bq@fDQ|@}@rEm@zCOp@e@`CsB~Jy@fEgDrPoBtJaCxLENqCjN{AvH}@jEe@~B_D~OwBlKSfA{@hEeAfFwLdm@Mp@kA~FQz@uBnK{@jEOp@CP_EbS{@jEGXGXiBbJy@|DkL`l@mEtTiAzF{@jEiAxFyBvKmAbGMr@{ChOuAdHkA`Ga@pBm@hDoBnKg@tCoB~JeDvP]~Aa@nBg@fCq@hDyChOiCpMsEhUS`AmBnJo@bD}@fE[zAOj@aCtJ{AnFaD~JwCdJaArCcCzHSl@w@~Bs@vBGRy@bCw@dCYz@Ur@ENSl@[bAq@nBc@tAuAhEy@fCs@xBSl@Of@cCpHkAlDw@dC}E`OSl@cCvHg@xAGPkAfDqAfDqAdDmBhE_BpDsCzF{D`IMTwJ`SWh@aEjIS^CFqCxF{HzOkGfMgAzBaBdDgAzBsIbQkGhMqAhCy@bBkRf`@{[hp@aEjIWf@iGhMgInPgAzBwEpJg@bAGLWh@gThc@{EtJoCxFsF|KgA|ByBlEgA|BqCvFWh@S`@uC~FWh@sIdQ{HzOqAhCk@nAkJlRiDbHaXxi@yHzOWh@cC`FaPb\\eAxBk@jAeQb^sF~KsOr[sIdQ{HzOWh@aGxLiJnR}@fBS`@Ub@c@~@gTjc@oYnl@Wh@iGhMqCxFWh@aBdDgA|BgAzBaBdDWh@iDdHwBhEsApCyEtJiDbHiD`HqF~KWh@se@haAaBfDaMdWcApBw@`BaBfDgAzBWh@}NhZWh@gA|Bo@pAWh@iAzBWh@gA|ByBnEWh@qCxFgAzBWh@Wh@iGhMaElIaBdDiGhMWh@gChFkCpFe@|@_AnB}BvEwHtO{KfUaHnNgA|BkMvWq@pAg@dAeA~BsGvM_BdDWh@cHtNaAnBg@fAeD~GwFdLwEtJUb@yKdUc@|@e@|@aElI}GhN]p@oDnHaDvGaPb\\eEvIiDbHo@pAaKzS_CzEyBtEsIfQ{KbUyEvJWh@cN`YyBnECFmBzD{BtEeBnDiDbHiDbHWh@oCzFcC~Ee@bAiGhM}Qp_@Wh@cHtN_F`KgAxBiBtDuLvVaHrNo@rAyNhZuR`a@sIhQWh@aKzSWh@IPcVzf@o@rA{KdUqIhQgA|BWf@MV}L`WWh@mShb@S^k@nA{Ulf@w^xu@sAtC_CzEaHtNyH~Oo@rAWh@qF`LgA|ByBnEwBpEsOv[aAnBkE`J_OvZsBfEWh@gKfT}MzX{Vjh@aAnBk]ts@aCbFyAxCwAvCqAhCme@taAki@phA_C|E}AbDeQn^Wh@{BxEeDdHi@pAQ`@y@xBkAdDk@lB{@~CaAlDw@fDuA~FsCrLeBlHkDhOYlA]tAc@jBK`@{@rDqEhR{FjVI\\kB~Hq@tCuB|Ig@tBaE`QgCrK_AzDwBfJq@pCsAxFyAfGa@bB}@xDeBhHwA`GQp@_A|DiBrHa@bBuBzIaA~D[pAqJha@mHb[]xAiAvEoArFkK|c@sAxFaCbKe@nBiF|TeNjl@yAhGkFbUuB|IOr@m@hCm@tCoJbc@oCfMaGhXOp@wBxJwB|Je@rBa@lB_AfEuHr]aE~QeAzE{FvW_BtHoC`M_DxNqB`JaSh~@oBbJs@`DoAzFOr@S|@g@~Bo@vCk@hCqCfMYvAeAvEoB`Jm@pCaBtHk@jCOp@S~@kCxLyDfQKd@Kb@s@dDoDpPs@|Cm@fC_@vAEJK`@_@rAm@lBWz@K\\c@nA[z@y@xB_@`Ai@lAi@lAsAzC{AjDiC`GQ^Uj@]t@Uj@_EbJy@jB]t@uA`D]t@Uj@Q^eO`]_AxBoArC_ArB}@tBi@lA_BpD}FtM{JdUqHzPo@xAWh@{AlDWj@oEbKWj@yDxIaDlHsBxE{IfSkK|UqRnc@Wj@Uh@k@nAiC`GmDbI_@z@mIhRuEpKuOd^cA`CiMvYuFbMmBfEm@zAeFnLkCbGoEdKQ^KTcKrUUj@qJpTuBvEUh@Yl@m@tAm@tA{AlDWj@eA`CwC|GqDjI_AtBEJO\\eA`CEJQ^EJyDxIO^EJQ^Uh@kAlCQ^Uj@cBvDaIvQa@`Aa@`AuBvEoGvN{AlDuA`DgAbCUh@mHrPaCrFaCrFKToBrEsBvEWj@sBvEmHpPgHfPkKbVWj@eFpLkCbG_CnFaDnH_BtDS`@qG~NiDzH}E`L}L~XcI|Qw@jB{AnDeBtD_@t@Wh@ABy@zAoA~BqCbFeAjB_AbB_BxCiAbC{@lBOZGNq@|Ac@bA[r@a@`AkAbCy@rBcBzD}AlDu@dB[n@]p@a@jAe@dAc@fA]~@GNM\\[z@k@dBKT_AtCaBvEUr@mAlDy@rB[z@i@xA[r@[t@k@rAcDnH_DnHWj@Uh@A?Uj@}D~I{FvMoCnGuCvGaBxD}AjDiHnPc@bAsCrGYn@aEjJsCrGuDvIw@dBs@`B_DjHaAxB{@rBsB~EEJ_@dA]bAOh@ADk@lB]tAOl@Qt@Mh@[xASjAQfAW|AS~AUjBGl@m@tFc@dEg@vEi@dF}@~H?DIt@OlAWhCSfBc@dEc@xDU|Bo@zF]fDUrBg@pEGh@c@`Ea@|Dm@xFiBnPy@|HWfC{@dIQ|Ak@fFIt@[zC}AzNiA`KuAlMKbAs@vG}@lIQbB_@dD_ArIo@bGmAjLgAxJ_@nDsBfRE^_@fDALmBfQyGtn@gAzJwCnXq@pGkAtKoB~Q}@hI}@rICRg@vEcCdUoAlLUzBmA~KGl@gBjP{@xHIv@AHeC|Ua@tD[nCMpAq@tGs@|GSdBOtAQpAMr@QdASbAe@xBg@zBsAbGWlASx@{AhHwArGaAhEu@`Dw@nDeCdL[tAeB`IS~@o@xCyEdTS|@Qr@kAnF}BlKwApGq@vCaDvNo@xCg@|Bw@nDoA`Gm@jCkBnI{@tDoAxFQx@_AlE_AfEm@nCeB|H_ClKg@xBuAnGs@bD_@dBeEpRoBxImArFGTG\\}AbHcBzH_BnHm@lCc@nBI^k@lCg@zBcDvNiAnFw@lD[rAYvAq@`DCJc@lBs@bDeArE}BpK]|A_@bBaAlEOp@ABu@nDGVOp@S`AcBrHYpA}BfKABu@lDq@bD]|A}@zDyB`Ke@xBiAfFkAjFgDjOqErSOr@_BnHyArGu@fD?@oA|FgBdIoA|F_AjEa@hBaAlE_@zAS|@y@vC]pAQn@qBlHeAxDaGhTe@fBELkAdEIX{@|CmBbHe@`BoFxRgBtG}@~CyFpSwBzHoC|JaCvIe@dBc@~A}AtFu@lCqCxJOj@aAtDM`@iAbE}BjIaB|FeElOgA~DoBfHSn@oAvEiDxLmGjUyE~P{F|S}@~CQn@iA`Ew@pCwB~Hm@vB{I~[Qp@Oj@}AvFsCdKaCtIiEvOQp@e@`B_CrIQp@eDtLY`ACJgAxD?@{@|CuAfFkBxGoBhH[hA_AdDIZe@fBy@vC{@zCo@~B{AnFOn@sAzEyAlFq@`Cq@bCy@xCe@dBSp@_@rAiAdEyAnFi@nBOj@Ut@c@~Ai@lBq@bC?BSn@Md@o@zBK^e@fBOj@y@vCa@zAa@tA_B~FYdAy@vCYdAe@dB}C|KaAnDaAnDCHw@pCMd@CHw@pCQp@Qp@K^y@vCg@lBMh@Sv@K^e@pBWhAa@pBW|AUzAKn@OhAW|BQbBKpAGv@?@MxBIdBCt@Cl@AHA`@Ar@CjACpAAzAA~C?vD?dA?fJ?X?bJAdI?nA?lP?|C?hD?|K?f@?lY?~@?lI?pL?|F?V?v@?nB?jD?`O?`BAlDAxB?DCr@Ar@Cv@EdACdAGhAIjAIfAGt@El@MrAS`BSbBOhASjAQbAUlACJKf@AH[vAOl@U~@Ux@Ut@Wz@Yz@Wt@Ob@a@fAUj@Sf@MXCFk@lAeBjD_B|CmA`CuDhH}AzCwCzFa@t@ILcApBoAdCyBfEyC~FqDbHqDdHa@v@Wh@aDjGsFnKaAnBiF~JS`@[l@Ud@m@fAu@zAgLxTq@pAiHjNqInPqExIMViAzBgBhD_HxMqAfCqGbM]p@cApByFxKWh@cBbDWf@{AtCa@v@Wh@q@nAwApCwApCcAnBaAjBk@`AU`@CBW`@m@~@c@l@Yb@[d@IHe@l@e@l@s@x@i@j@e@f@[XmBdBsAhAs@f@a@V_@V[RgAn@iAj@{Ar@{@ZkA`@e@NqAb@GByIrCYJE@mA`@kGrB{C`As@TwDpAwAb@cCz@iAd@e@TWLc@RkBfAuBbB]X?@wAvA{C`EcAfBq@nAEFe@dAe@lAaApCm@lBs@rCw@jE_@pC]rC]`EG~@GrAGlBE`CCrBEfN?zAAj^?fB?hA?xAAzDExIi@jMk@jGW`B]bCm@xDOt@Or@a@vB_BnFu@vBWn@kArCyBfEeCdE[b@]`@m@v@eBjBqBnBaEvC}BrAq@`@gB`As@^sAr@oCbBoAv@sD~BuCxAqDrBgBv@A@_CdAkA^_Bh@mA^eAZc@LGB}B^G@cEb@kEVsOFyBB]?s@AwBAaC?cm@@gA?kB?kE?uADw@DmAJmAL{Cl@wDrAuCrAkCbByDrCcFrFy@nA{A~B{DrG_NtUyDvGo@dA_BpCW`@_E`HgJzOaDrF}@pBwA~Cq@nB{@`CeAtDy@dDgAjGYnBKt@[bC[tCStBSjDIrCCv@Av@Aj@CdF?bAAbVArPDnm@CdFAbB?pA?dB?tA?nC@fM?~^@`O@hT?tI?jD?v@@|V?rD?n@AfB?HG|E?tI?bVAxP?pR?lKAhk@?~A@rA?nB?R@xDApR?xP?pA?~J?lO?V?`@?fM?r@?B?fO?`C?`@?nC?lQ?xE?`E?~N?b@?TA|N?jD?x@?pE?zL@pUAfB?xP?h@?nL?rJ?P@lE@zCA`A?dE?v@?zF?pE?r@?hIAjD?tI?H?x@?dB?rA@rUA|R?jU?vD?T?nE?xC?|W?bI?tV?v@@~CAfH?D@pM?xC?ne@?fE?bB?lAAlQ?~B?x@A|Q?pT?LA|K?xC?~EAtB?~N?lC?nBApCCfO?v@?bF?lB?jD?hD?bF?lJApR?jT?nL?bF?V?b`@ApF?lEA~^?x@?hT?pBA|G?fMA~o@?dF?DArDAjd@?x@?hS?tFAlE?|G?bF?`FAbQ?zN?fGArF?rF?pB?x@?bV?hD?x@?jd@?bF?hD?x@A~N?x@?dM?`I?jF?pR?hD?jD?bF?bFA`F?|G?pB?bF?tI?bF?v@?pB?pBAjT?rI?bF?dF?bE?x@?hD?pBAldA?bf@?lJ?bF?x@?v@?^?x@?v@?x@?pB?`B?fA?h@?jD?L?h@?L?tE?hD?jD?`D?F?x@ChD?B?HAj@CbA?@Ch@E`ASjCC^Eh@E`@UpBANKr@?BO~@QdASfAa@dBMf@CH]tAYbAWz@g@tAADMZEJe@hAi@fAy@xAo@hAmDrFS\\qAnB{@tASZu@jAwCvEwBhDQVeC~D_F|HyDhGu@jA[d@kGzJYd@SZqB~CwEnHYd@qAnBYd@u@jA{DfGu@jAOT{PnX[d@_DdFYd@eC|Du@jAYd@[d@oApBoFvIcDfFoClEoClEkBvCkBvCYd@aDbFy@tAQVGLYd@Yd@[f@s@lAYh@_AbBmAnCCDUl@i@vAg@tAYfAe@jBq@bDk@pDQnAUtBSpCKhBKlC?TCx@Av@AhHAlP?hD@|G?hD?xH?vE?dA?dL?v@?bFAv@?x@?hD?pB?x@?v@?tI?x@?bF?v@?bF?x@?v@?pBAjT?x@?hD?x@?bF?nM?xOArb@?hD?bF?|GArb@?|RAx@?f@?xK?nL?fK?fM?x@?x`@?tIA~g@?rAA~L@dL@vY?v@?dV?v@?xP?x@@zG?fM?~O?nD?vA@zH?nE?pD?lK?ld@?df@?b[?tF?zG?x@?x@?tD@~Y?x@?f]?v@Bhm@?xG?nP"
                     },
                     "start_location" : {
                        "lat" : 50.3953663,
                        "lng" : -105.4773703
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "40.0 km",
                        "value" : 39999
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1586
                     },
                     "end_location" : {
                        "lat" : 50.9073792,
                        "lng" : -113.5367581
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAB-901 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_jmuH~jvpTfAAjACb@AfAAD?|AHf@FB@h@PXLXJFD`@VpArAn@|@|@hB?@jAjCh@jAJXHNdCxFbBvDVh@n@tAl@tAzB~EP`@|AjDn@tAjDvHjBhEBFfA~B~AlDTh@@@Tf@?@Vj@~AhDVj@Rb@Zr@`A`CVj@Tj@xAlDfAbDtA|ENf@@FDLjAbFhAnGXpB@BNhATrBNjALlAJjAPtBFbALfBLjCDjAHvCFvD@lG?~I?v@?p@?bH?x@?v@GzO?~EAxJAvEAnEBtJ?pA@tI@zD?nBAfE?hLA`CFrUAnG@fHAzGBbDBfA?VJ`EJzC\\rFPfChAbPx@pL~@`NRfDvA|STdDBTTbGJlCAbFGlDAVGv@c@dIgAbMGv@eAxLs@jIGt@k@tGIt@q@jIc@|Es@jIc@zE{@bK}@`KC`@WbCKbA[bDIz@gA|HcClQc@`DkB`NWjBuAvJ{@jGsGre@UfBKr@c@`Di@`EmAvHqApGkAtEe@~Aq@tBkAzCgAjCsBfEmCvEwLbS[f@kK`QsEtHyFjJwBnDkAjB}CtFyAlCcCfFg@hAuDxI_@z@Wj@sBxEsAtDa@hAsAdEU|@oCfL_CbJgAxCSl@_@~@}AbDQX{@vAeA~AiC`DoBfByCxByA|@}DrCqCvBuAjAaA`AoAvAcArAw@nAq@fAc@z@Yh@ABs@xA_@|@_@dAy@~Bq@~Bc@lB]`Bg@rCg@bDe@lCMbAa@`CKn@SbAi@nCWjAIXu@rCSl@e@`Bo@tBgCxGwB|F_BdE}A`E}@`CEFUl@i@rAq@hBMXq@lBm@~AQh@kA~C_@dAIPoAfD}@`CyAxDCHM^O`@CLs@zBIVqAnE{AdHu@xEGf@ABKt@MfAg@fEKnAGx@AJSfDI`BIdBCt@Cr@A|@GjBAzC?|DArO?n[?nK?pB?|G?x`@?x@?pB?zG?bF?|G?x@ApB?hD?|G?td@?pk@?pB?|G?v@?jT?dV?x@?fM?v@?dV?vG?tI?rR?n[?x@?tI?nk@?rRGlU?dD@tBGxO?pC?x@@jT?bF?pB?bF@|G?hD?xP@|G?bF?hD?jD@rb@?nt@@n[?tR?rb@?jD?|W?fM?pB?x@?v@?`O?xP?x@?zTElMEnKAv@AdFAv@E`OCzGApBCbFC|GElKApBC|G?pBElKAx@?~@UlIO`FQxDShDCb@El@SdDAJGt@a@rE_ApIQ~Am@jE]`CI`@_AjFk@zCKj@wB~JmClL_B`HaAjECJs@fDeAnF_@bCSrASvAQnAS`B}@bHw@jIAPGl@]hEQlCUvDGjAE~@El@Aj@GzAE|AMxGE|A?RUzKQrICj@IbFIdDKfF?HAl@GrCCnAA|@GpCOjIc@lSgAji@g@pXGdDM`Ge@nUGnDCvAE`CCj@GhDMfDGpAGpAKzB]dFO`C]bE_@zDc@xDCPY|BWfBGb@?Be@~CG^ERe@~Cg@~CKr@e@rC]vCQhAY`BMx@k@fDc@vCQlAc@vCWtB}@rHOjACZAHa@zDSlBk@bGUnC_AfMc@xFSvDGrACf@Ch@Cf@MdDErAKfDErAIhDIlDAjAKlICpBAdC?l@Al@AbF?zB?lU?zJ?h@?nI?pD?`E?pLHdoABdg@IhLGnIOhKa@p]ErDEdKApA?zCErXE~VAfEAfICnI"
                     },
                     "start_location" : {
                        "lat" : 50.863844,
                        "lng" : -113.0054361
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "25.1 km",
                        "value" : 25052
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 911
                     },
                     "end_location" : {
                        "lat" : 50.907117,
                        "lng" : -113.8914881
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eAB-22X W\u003c/b\u003e (signs for \u003cb\u003eCalgary\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAlberta 22X\u003c/b\u003e)",
                     "polyline" : {
                        "points" : "czuuHvc~sT?xV?|O?nG?h]?hI?vDBrb@?~K?`B?tI?tI@pk@@tb@?xP@nK?zB?jDAzF?zA?|FDfGJ`IV|JHxBNjD@RJ~BLlCh@`JLhBj@lI~@vNb@vG?BlAxQb@zGTfDDv@Df@dE|o@TfDpB|ZDv@TlDNbCRhDFfBBd@@d@?PBzBBpCAjCCrBGdDK|BGvAInACj@QtBS~B]hCOnAStAc@bCg@dCoAxFaAlEm@fCOp@q@vCADq@|Cc@lB]lBg@vCYtBGd@_@pCSdBc@pEUnC[fGI|BGbBIvCE|BAhBAzA?hC?rG?zA@~D?lD?d@?fC?dC@`J?jH?tG@zD?pB?bC@hI?vG@`G?rA?v@?bF?pB@h@?N?hD?pB?xD?bB?pB?\\?rA@zA?pD?zGA~LA`D?p@CrRAzJ?lBAv@Kzy@CjKAtNB~O@tB?rB@bB?jE?v@@rD?rD@xG@|O@fF?tD?^?V?pG@bA?pB?|B@dB?x@?bC?vC?`A?p@?fD@~G?`B?dC?pA?`C?R?`@?xAClCCdC?HGxCGvB?@GbCMrCI`BItBIxAMdBK`BShC]xE[nEW`DANY~D[jEC`@YvDc@bGEv@UzCOvB?BQvCGfACf@K`C?NCf@C~@GjBIhCEfBA`BC|AAnAAnCAfB?lB@hB@vBBxCD`B?NBvAL`EH`CPdEFbARlDR|C?Bb@`G`@rF@JDj@VpD\\tETdDT`Db@dGTrCJzAHlAVnEJxBBh@Bx@JrCFjCJ|EB~C?NB|C?P@nF?j@?bD?rEA|D?`I?`@?vJ?vC@rO?x@?v@?tE@p_@?lK?rR@b_@?v@?bF?x@@~N?x@?~g@?x@@tT@z`@@p{@A|p@DnR@v@?h]?x@@pB?v@?bF@ff@@pS?|@?tI?`E?rB@xD?fE?F?rE@hC?|@Ax@?rD?`G?P@~F?hC@pJ?tA?vC?jA?nB?`B?jA?v@?nE?dF?~@@J?fH?hF@tBAlI?z@?hAAvBAbE?rE@dGBp_@"
                     },
                     "start_location" : {
                        "lat" : 50.9073792,
                        "lng" : -113.5367581
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2428
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 50.906958,
                        "lng" : -113.9253674
                     },
                     "html_instructions" : "Take the \u003cb\u003eAB-201 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eStoney Trail W\u003c/b\u003e ramp",
                     "polyline" : {
                        "points" : "oxuuHxlcvTARAd@?lA@tA?lBAx@?nA@v@?h@?jA?lEBl@?v@?jB@`E?^?TB|HBtFDjEDjFDhCDrC@pA?nA@^AfBAx@ErAAt@E`AIjBCf@IhAEn@Ix@Ed@Ix@Ix@OrAOhAG\\QpA[lC[lC_@hDSdBI|@Iz@IzAE`AAn@Cr@?dA@x@?@BdABz@F`AHjALjAFf@@DLx@VtALn@DNT`AJd@J\\@FBFZnALn@FZPdABTBLDf@J~@HdADr@Bj@BjA?VBj@AD@|@ArAA|@AX?x@ATFr@"
                     },
                     "start_location" : {
                        "lat" : 50.907117,
                        "lng" : -113.8914881
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2617
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 93
                     },
                     "end_location" : {
                        "lat" : 50.9028629,
                        "lng" : -113.961905
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eStoney Trail SE S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-201\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-22X\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "owuuHp`jvTCxDA`AAnAA`EA~A?rEAt@?|B@fC@dC@xA@~B@z@BfABhAD|A@NDjBBdAb@tILhCB`@P`DHhAJxALdBj@xHFt@NjB?BD^@RTfCXtC^vDBV@DFp@@BJhAHv@p@~GbA`K`CzVFh@Fv@Hv@ZdDTnCXlDt@`JZvDAl@?LHjAj@dIDd@Dd@"
                     },
                     "start_location" : {
                        "lat" : 50.906958,
                        "lng" : -113.9253674
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20.7 km",
                        "value" : 20747
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 751
                     },
                     "end_location" : {
                        "lat" : 51.0435664,
                        "lng" : -114.008958
                     },
                     "html_instructions" : "Take exit \u003cb\u003e101B\u003c/b\u003e to merge onto \u003cb\u003eDeerfoot Trail SE\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-2 N\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{}tuHzdqvTCT@N?JF`AT|D@FLrBXrF@VBR?JNfCFbAHhAJrAH|@Fp@Df@B\\@DDh@Fx@@JBj@@J@`@@f@?~@?F?f@A\\Ch@Ad@ATCTCZCTEb@EZGXEVIb@ABI^U|@Ur@Q`@Qb@Wj@_@l@k@v@SR]\\CDSNMLeAj@_@Py@VeAReBRG@c@DoANYDeAJk@BuADQ@GBE@OJk@CC@WTkB?cBBeKDUAi@@qD?cI?uD@eA?eF@iN@{G@C?wC?wA@qC?uI@u@@i@?g@As@?kJ?sDAiCB]?w@@_D@[?iC@mD?eC@y@?I?wB?a@?yF@eF?sA?W?]?c@@yCDq@@{AFo@DW@uC\\]HcARo@P}@Zm@T_@PqCrAEBOH]TQLsBzA_@Zg@b@s@r@q@p@gAnAu@`Ao@z@u@fAA@KRU^s@nAYj@QZS`@Ud@Uf@c@`Aa@fAq@jB_@dAUv@u@jCSv@YnAa@nBGTe@jCYdBUjBM`Aa@|E]~EMnBA^Q~D?DS`EMnCStEM`DEz@MhCi@jJInASlC?DIz@Gt@E`@SnBGh@UlBCXIf@QvA[`CWdBUzAEVW|Am@hDo@vD}@fFq@|Dy@zEo@rDu@jEc@jCgAjGAH]vBa@lCi@fEYnCMpAM~AUlD_@xF[pEQzCO~BItAKvAYvCUdBWdBSpAWbACNGTGXAD_@vAGTq@hBSb@Q^Q^Ob@[p@OXGJu@lAm@|@_@d@uAtA_@Ze@\\}AbAo@\\_@R]NC@g@PKDSF_@JSFMB{A\\_@J]FG@_B\\aB\\yAXs@L}@PSDqBb@w@NQDWFm@NkDx@oCn@WF}@PmAZq@Pq@PWHIBsAb@e@NqAf@_@P]P]Li@XA@o@ZWNeCxAmAz@i@`@g@^_@XA@g@`@UToBhBQNIHMNcAbAk@l@w@~@]`@i@l@wCbDoBxBoApA{@|@y@x@[VOL_@X[T]Tg@V[Pm@Xa@NQFKDIBu@Ri@J]Fg@DWBc@Di@@cADe@@g@?s@Cc@AA?MAMAUC_@E_AMICo@Oy@Uq@Uc@Q_@O}@c@{@e@{@g@yCoBcEoCeAu@m@a@GCOKSOCCECKGWQoAy@s@e@MIiBaAi@Y}Au@aBo@[M]KaDy@aAQg@Ii@GsAOsAKkAAkAAwE?a@?y@?_@?qA@kE@W?gB@_@?O?IAICe@@a@?KAW?g@Aw@C]Am@EC?k@EQAk@Ga@E]Em@K_AQC?a@KC?k@MqA_@m@S}@[s@[s@Y_Ac@GEa@QIEm@_@qEkCi@]AAc@Ym@_@c@YKG[Sg@[m@_@k@]e@[i@]g@[u@c@k@_@e@[MI_@Ue@[m@_@k@]OKc@Wk@_@s@c@g@]MI_@UIEIGsA{@u@e@i@]CA_@WQKg@[c@YYQ]YKGSQ[YSSUWGG]c@g@s@Wa@Yg@Ui@Se@Qc@M]CIOg@Qi@Mk@Qu@?EAAKo@Ko@Ik@Is@Iw@CQ?CEi@EaACw@CeA?q@?i@@_ABiAHqBDkANuCD{@JeB@q@?CBy@?C@s@?C@u@Ac@AmAA_@Ci@Ew@?MG}@MmAMgAAIOiAGa@GYUmAOs@Ou@Oo@CMU}@YeASs@AEy@_C]}@_@aA]w@o@yAg@aA]q@q@qAw@sAc@y@]g@eAwAk@s@OQi@i@qAsA[[oAoAYWw@o@_Ao@MKo@_@g@[u@a@iAi@qAk@i@UiCcAMECAk@WyB{@eIaDkCeAw@[{B{@q@WaA_@w@]}Am@]Qc@S{D{Ac@OMGOEWMaEcBc@OiFoBaCaAuBy@cCeAwB{@i@SmBo@q@Qi@MaBY{AImAAm@Dq@H_@Fu@PwChAUN[POJMHOJYTONWVs@t@s@|@o@`Am@fAGN_@x@e@hASl@Ul@Sn@K\\gAjDc@rA]fAWl@Qb@MXSd@S^QZS^U^SXKNW\\m@p@c@`@SNWR[RUL]Ne@RC@OFYJm@Ty@XcA^_@N]L_Bl@cBl@iA`@w@Xg@P]Ny@^_@VqAx@{@r@y@`Ae@n@QX"
                     },
                     "start_location" : {
                        "lat" : 50.9028629,
                        "lng" : -113.961905
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 240
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 51.044988,
                        "lng" : -114.0114365
                     },
                     "html_instructions" : "Take exit \u003cb\u003e256\u003c/b\u003e for \u003cb\u003eMemorial Dr\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "impvH~jzvTM@G?A@A?A@EHGHU\\S^QZU`@IPABSb@Sf@Qb@KVGR_@hAe@|A"
                     },
                     "start_location" : {
                        "lat" : 51.0435664,
                        "lng" : -114.008958
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.8 km",
                        "value" : 2825
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 184
                     },
                     "end_location" : {
                        "lat" : 51.0498073,
                        "lng" : -114.0471329
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork, follow signs for \u003cb\u003eMemorial Drive W\u003c/b\u003e and merge onto \u003cb\u003eMemorial Dr\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "evpvHnzzvTaBlFQj@Oh@Qh@MZKVKVIPKPMPKLMLKJMJOJA@ULC@SHUHYHgAZ]J_@LWJSLC@OHED_Ax@ONUXW^Yd@OXCFGNGPENENENGXCPERKn@CXCX?V?P?X?R@V@`@?JHhAFj@Dj@Lx@FZH^FVHb@`@~A`@`Bj@bCZvATjANz@@@Fd@NtAJdAN~ABh@Bf@@N@f@Bx@B|A@vAAfA?H?p@Ah@ExACrAEvAKtB[nEUdDM|DCfAAjADvGFxG?t@?p@Al@Ab@Ep@IlAGd@Gd@Mp@a@dBUr@c@rASn@Sr@Sx@U`ASpBKbAKrAK`BEv@Ap@An@?r@?j@@f@@`A?R?F@Z?R@~@?@?v@?J?^A`A?DAj@?L?DAp@E^AZE^KfAIh@Ij@Y|AKh@"
                     },
                     "start_location" : {
                        "lat" : 51.044988,
                        "lng" : -114.0114365
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 758
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 51.0491472,
                        "lng" : -114.0559083
                     },
                     "html_instructions" : "Take the \u003cb\u003e4 Ave S\u003c/b\u003e ramp to \u003cb\u003eCity Centre\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "itqvHpyawTIPENCHI\\Wx@Ob@EJa@`A_@|@c@dA]t@Un@AFMh@Mn@Gd@AL?FAX?Z?f@@J@T?FBZ@@BRD\\FVDN@DDH@HJNDJTb@DDLPDFLNJJHJXXDB^Z?@b@`@TV@@FJBBLP@BBFFHBFBD@DBDLZLZHXFVBFH^DRBXBP?@@R@R?N?N?tAAZA|@?DD^"
                     },
                     "start_location" : {
                        "lat" : 51.0498073,
                        "lng" : -114.0471329
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1236
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 160
                     },
                     "end_location" : {
                        "lat" : 51.0496518,
                        "lng" : -114.0735756
                     },
                     "html_instructions" : "Merge onto \u003cb\u003e4 Ave SE W\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "epqvHlpcwTChDCvEIrJAzBKhJCbC?~@CzDGnFClCG~IQ|MG`HG|FEtC"
                     },
                     "start_location" : {
                        "lat" : 51.0491472,
                        "lng" : -114.0559083
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 479
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 123
                     },
                     "end_location" : {
                        "lat" : 51.0453477,
                        "lng" : -114.0739125
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e5 St SW\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "isqvHz~fwTxAHdAF`@B`@?v@Bv@@b@@T@Z@X@RB|ADD?F?H@dADz@Bb@BfBB"
                     },
                     "start_location" : {
                        "lat" : 51.0496518,
                        "lng" : -114.0735756
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "47 m",
                        "value" : 47
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 51.04493590000001,
                        "lng" : -114.0738724
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003e5 St SW\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "mxpvH|`gwTPK~@B"
                     },
                     "start_location" : {
                        "lat" : 51.0453477,
                        "lng" : -114.0739125
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 140
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 29
                     },
                     "end_location" : {
                        "lat" : 51.0448403,
                        "lng" : -114.0718702
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003e9 Ave SW\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{upvHt`gwTN}HBqA"
                     },
                     "start_location" : {
                        "lat" : 51.04493590000001,
                        "lng" : -114.0738724
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "261 km",
                  "value" : 261098
               },
               "duration" : {
                  "text" : "2 hours 58 mins",
                  "value" : 10652
               },
               "end_address" : "Radium Hot Springs, BC, Canada",
               "end_location" : {
                  "lat" : 50.620042,
                  "lng" : -116.0733609
               },
               "start_address" : "Calgary, AB, Canada",
               "start_location" : {
                  "lat" : 51.0448403,
                  "lng" : -114.0718702
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 271
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 51.0447278,
                        "lng" : -114.0679948
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003e9 Ave SW\u003c/b\u003e toward \u003cb\u003e3 St SW S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBarclay St SW S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gupvHdtfwT@_@?Y?I?O?A@O?_@@_@B{BH}J@gB"
                     },
                     "start_location" : {
                        "lat" : 51.0448403,
                        "lng" : -114.0718702
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 318
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 105
                     },
                     "end_location" : {
                        "lat" : 51.0475827,
                        "lng" : -114.0678431
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e2 St SW\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qtpvH|{ewTA?o@?W?Y?wAAwDOI?G?yBGy@C"
                     },
                     "start_location" : {
                        "lat" : 51.0447278,
                        "lng" : -114.0679948
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1687
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 214
                     },
                     "end_location" : {
                        "lat" : 51.0473909,
                        "lng" : -114.0914958
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e6 Ave SW\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kfqvH~zewTM`NE|FKlGAn@AxAA`@?`@KfMGtFEzFKdKAdBMzM?L?JAVIjMElCCbDEnD@VExB?d@?@?V@R?N@N@N@N@N@H@DBNBLDPBLDJFTBHDFBHDFFJT`@r@nALT"
                     },
                     "start_location" : {
                        "lat" : 51.0475827,
                        "lng" : -114.0678431
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "22 m",
                        "value" : 22
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 51.04725260000001,
                        "lng" : -114.0917139
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003e6 Ave SW\u003c/b\u003e, follow signs for \u003cb\u003eBow Trail W\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "eeqvHznjwTZh@"
                     },
                     "start_location" : {
                        "lat" : 51.0473909,
                        "lng" : -114.0914958
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 218
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 51.04699309999999,
                        "lng" : -114.0947424
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003e6 Ave SW\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "idqvHdpjwTRx@J`@DVDVBZ@X?Z@t@?p@?hF?N?F?H?J"
                     },
                     "start_location" : {
                        "lat" : 51.04725260000001,
                        "lng" : -114.0917139
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1006
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 51.0451255,
                        "lng" : -114.1080211
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBow Trail SW\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ubqvHbckwT?L?@AL?^At@An@Cd@A^KbAOnA?BG`@Gp@El@CRANCx@?DKjDIbEGdCA~@?n@@n@Bl@Dh@B\\Fh@?BJ~@VzAh@pC@JTdALb@ZjAT~@JZLb@Nf@ZbAp@jBp@tBx@~BDJr@rB"
                     },
                     "start_location" : {
                        "lat" : 51.04699309999999,
                        "lng" : -114.0947424
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.4 km",
                        "value" : 4376
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 337
                     },
                     "end_location" : {
                        "lat" : 51.0524534,
                        "lng" : -114.1636721
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eBow Trail SW\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "awpvHbvmwTf@bANb@Nd@x@dC@Fv@~BX`A|@hDBHr@dCVz@x@pC@BXdARr@Pr@j@`C^dBHd@BLBVBLJn@DZZxCDl@Ht@LnBDv@Dp@@PBv@@n@?H@^?V@x@?@@h@?J?Z?f@Ad@?H?`@Ah@Ad@Al@GzBAl@?h@Af@?V?N?h@AdD@pL?nB@jB@lB@hBHjH@jA?fA@hA?fA?`@?rB?v@?jH@hBAbDCtBAX?XAVAT?@CTATGb@GZI\\IXI\\KVGPO\\ABMREFKPMTOROPQNQLQLOHQHSDSDKBw@PSHQHMHOJOLMNKNQTINCHEDCFGP?@MZg@xA]rAe@dBc@`BKZMf@Qn@k@fC_@fB]~AkAlFcClLI\\mCjM}@pEOn@q@bDERqAfG_ArE_@dBOr@K^u@jDI\\aCvKoBlIQn@m@zBQv@c@hBI\\i@pCMp@Sz@ELM^?BQp@M`@GTKTSl@"
                     },
                     "start_location" : {
                        "lat" : 51.0451255,
                        "lng" : -114.1080211
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.1 km",
                        "value" : 3110
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 154
                     },
                     "end_location" : {
                        "lat" : 51.0745995,
                        "lng" : -114.1860187
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSarcee Trail SW\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ydrvH|qxwTSNKJEDQNKFKFMDM@KBW@Y@G@GBSJoB?uA?W?I?yB?cA?m@?m@?o@Ae@Ae@Am@Cm@Ci@?Q?MAi@@S?q@By@DC?[BkALc@Fs@Lk@J[Hm@Nk@PaAZ?@A?c@NQHq@ZUJGDUJe@Tk@\\A@[PKFULQLk@\\a@Zw@l@WRg@b@e@d@STYZaAjAEDW\\CBABUZCDA@]d@U\\A@QZGHYf@A@KPMPIPMTYh@Wd@A@OZGLOZGLABUf@A@KVGP_@|@KZOb@EHSn@A@Qj@A@Ql@ABGNIZSn@AB_@|ASr@Kb@EJABOl@ABQn@c@~AAFOf@YdAe@dBKXQl@ABQj@K\\gAdDc@nAaAhCWp@Yp@cAbCcAzBWj@ABWf@Uf@S^EHuAhC}AnCILk@~@i@|@g@p@{AzBg@r@e@j@s@`AgApAcAjAq@t@CB{@~@qArA"
                     },
                     "start_location" : {
                        "lat" : 51.0524534,
                        "lng" : -114.1636721
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 322
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 51.0772638,
                        "lng" : -114.1877406
                     },
                     "html_instructions" : "Take the \u003cb\u003eAB-1 E\u003c/b\u003e ramp",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "govvHr}|wTSBG@I@OFQP_@^]XCBy@l@A@_@XA?[Vg@X]TMJcA`@k@RkAb@"
                     },
                     "start_location" : {
                        "lat" : 51.0745995,
                        "lng" : -114.1860187
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.0 km",
                        "value" : 2975
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 161
                     },
                     "end_location" : {
                        "lat" : 51.0861808,
                        "lng" : -114.21987
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e, follow signs for \u003cb\u003e16 Ave N West\u003c/b\u003e and merge onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-1 W\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "{_wvHjh}wTc@NEB[LEB[LMFSLE@[RQHMLEBYVCB[VEBWXA?ABA@[R?@IFWJKDWFc@DK?Q?q@?c@?a@AIA[AQ?c@CUAu@EWEOKCAIOGSEQAQAQ@S@OBKDOFODGHG@AHELGNCR?F?J@RFPHNJ@@FHFLBF?@BDDPBT@T?L?NANAV?J?Xk@|C[|A_AlFShAY`BKj@AF]pBW`BGd@Kz@Gb@IfACVGjAI|AAd@EvBAJ?^CbCAvI?~@@|D?jAEhDAj@E`BGfCYxECh@ALa@|EGp@Iv@OpAYhBuAlJ[pBKp@AHGX{ApIy@pEk@hD]bBOp@o@|COt@c@zAc@lCMv@Mr@i@~C]pBMr@O|@Kj@CLa@pC"
                     },
                     "start_location" : {
                        "lat" : 51.0772638,
                        "lng" : -114.1877406
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "142 km",
                        "value" : 142049
                     },
                     "duration" : {
                        "text" : "1 hour 23 mins",
                        "value" : 4978
                     },
                     "end_location" : {
                        "lat" : 51.26331159999999,
                        "lng" : -115.9272443
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003e16 Ave NW\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAB-1 W\u003c/b\u003e, follow signs for \u003cb\u003eBanff\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Trans-Canada Hwy/\u003cwbr/\u003eAB-1 W\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "swxvHdqcxTQdA[tBQnA[tB{@rF[tBWdB[nBc@`DETStAa@vCWpBMfAGh@Kx@Q~AOnAIdAIfAIjAGjAGjACv@CfACjAA`AA|@?fBAdC?v@?z@?nBAlD?|I?jDIlJAhBEpCANAh@?LKnGMzICdBCrBA^CbCApC?rC?\\@|@?|A@hA?jB?D?Z?Z?B@~E?b@?R?bFAnF?fC?vDFzI@r@?DB`FL`G?VD~C@dBA~G?rG?rPAfV?pB@vI?pB?rB?v@?pB?rB?fD?tBAx@?v@A|QBhL@v@?`C@zCBxFB`N?lAAtC?jDAfA?zCAjD?x@AjD?f@?zDAbEAlEC~F?v@?x@AlAB|G?pB@|BH~K?n@AtM?dBAbE?X?xA?lG?~A@bCC~@?dA@~B?lF?p@?F?^?V?x@ArI@dGAlF?r@?D@hCAdP?VAjJ?|L?|H@t@?pD?lBAvK@`G?zB?J?bCAhH?Z?@?`K?xD?@?dF?rF?`F?`ABzW?Z?\\AnK?P?H?x@?x@?P?D?zA?N@\\?D?T?fA?vD?jD?|CAdF?`D@lJ@hM?D?`VAnGAfN?~F?N?jF?nD?xE?fA?bI?~E?zK?vI?lAApD?nD?@?zC@zH?rN?@?v@?dG?tD?L?x@?pB?xBAzF?lC?v@@b@AfC?x@?|@?`K@`D?dC?nF?pL?nO?J?d@?vC?fF?tC?pE?zB?fN?nD?fF?nC?dI?P?zH?zH?j@?|K?|@?V?vA?hA?bB?vB?bC?^?bA?tE?B?dF@b@?~D?tB?nB?N?hA?t@?n@?b@?zC?rB?|B?|B?`C?fA?vF?H?`P?zA?f@@|@@lB?J?`@@hA@X@n@BnABhADjABp@@ZBn@Dp@FjABr@BXDp@HhAHlAJfALvAPlBJjAJhAFn@Hr@Fn@Fp@JfAJjANbBTxBb@zEX~CPtB@JFf@PhCB`@@P@ZB\\D`AFnA?BDdADjA?VB^@l@@X@bA@b@B~B?r@?J?`A@p@AnA?|AAlA?F?R?x@AjAGlI?n@ClFC`FApBAr@CnKApBAx@?bBALAlD@V?Z?bBCvGAlBAr@?bBGdNArA?DAjC?hBAxAArDE|JA~CAlD?`@CvGCbHE~JAxEAbACbGEnOGdOA~B?@?x@ApBA`DCjEApBAxEA`CAvCAdB?lAAxCAjA?h@Av@?v@A~B?l@EnKA~@ClJEhMAfAAjDApEAdCC`FAlE?XAn@A`C?p@?@AvCCvFCpF?t@?@CbF?x@?v@EvHAhEA`CAbB?ZAvA?fBCxE?pAAjCAv@AzB?Z?^?TATC~F?nAAr@Ah@C|@Ar@Cp@Ez@IjAEv@Ip@KlAEf@AFMhAKr@WdBi@lCQ|@S|@a@vA[~@ENKZW|@CDSl@Sn@M`@O^M^EN]bA_@fAa@lAm@jBMb@[z@M^EJc@rAK\\}@lCUr@U~@[`As@dB?@Un@Sp@e@zAOh@[fAMj@On@WrAET_@~BGd@Ip@?@ShBGp@?DI~AItBEvBAtB@xA?J?F?FDpADjAJ`BHz@@J?JBRRfBVhCLfAPzADb@@PBLP`BNtANrATbC^zD^`DTnBTtBFl@JfAhAtKVlC^~ELtBN~CB`AD|@@t@FxCBxB@fC?`B?fBAjBGhCC|ACpAK`CKhCQdDEp@a@dFQlBSlB]rCu@`F]nBSfAMl@]|Aa@tBa@tBk@nCe@zB{@dE_B|HiBrIUfAaBfI}AnHYxAaAtEk@nCw@vDc@tBaArEc@tB]|AMl@Ml@WhA[zASbA]~Au@xDUhAYxAmAbGo@bDI^CJUdA_@dB[rAs@lDCNqAhGeA`Fi@nC[zAUlAYzAq@`Dq@dDs@bDm@vCQx@a@vB_ApEk@jC}@rEg@~BCHmAdGc@rBK`@YtA[zAw@zDc@rBc@rBs@fDc@tB[|AGXMl@UhAa@nBSdAgAjFc@rB[~A]~AQx@Qx@[|ASdAUdAUdAKl@WfAi@nC[|A[zAe@vBa@rB[zAc@rB[|A[~AA?a@rB]|AMn@Or@EN[~AOn@Ml@k@nCa@nBGZi@hCKh@WjA[zAUdAUdAcAxEUlAUhAGXIf@G^e@vBc@tBS`AUjA[xA_@zAUbAYdAW`Ac@vAa@vAc@vAc@vASp@gEvN_EbNgApDk@lBk@lB{@nCQn@aDtKK\\_@lA_A~CABy@nCQl@g@`BCHm@rBq@xBs@bCi@dBELY~@a@xAc@vAMb@Sr@i@hB}@vCIZSn@g@dBe@zAEP}@xC[dAQj@AByA|Em@rBOh@ADgCnISp@Ql@q@~BeErNoAdESn@Qn@ABg@dBg@~Ao@tBq@zBk@lBq@zBQl@A??@Ql@mDpLWx@gArD]hAADSr@K\\q@~B{AdF]fAcAhDsCvJ_@lAADCHSn@qBbHSn@Qp@u@~BKXwAzEMd@OX{@zCqClJy@jCABw@jCAD_@rAs@zBw@nCQj@[fAENw@`Ci@lBGVSj@Ql@Ql@Qj@KZENOh@c@vASr@uBfHQh@Ux@kA|D{@zCs@~BEN_@pAQn@Sp@i@jBy@pCMb@Wz@K^Ut@]lAWx@Ux@Od@CH[dAENWx@KXGT_AdDSn@Sp@_@nASn@Qn@g@`BM`@CLg@~Am@tBa@vAu@`CeCnIEN_@lAGRe@~Ae@`By@nC?@{C|JgBfGIVaBnFIVu@hCi@fBSn@a@pAY|@Sn@Qn@Yz@Qb@CHGPKXGNM\\O^ELSd@ADYp@KTQf@Uf@[r@g@fAa@t@EH_@t@KPk@bAGJcAhBILe@z@KRs@lAcAbBc@x@QZGLmAtBs@nAS^aBxC_AzAYd@QXa@t@Yf@QXYf@Yf@GJk@bAGJyBzDYf@Yf@mAvBEJeAjBYf@GHk@dAA@EFk@dAGHWf@S\\EHS\\A@w@vAS\\EHgAlBYf@A@CDS^A@CDUb@_CdEkArBuDvGABWb@A@s@nAw@xAk@hAUd@KR_@~@g@vAUv@CDOh@Sl@{@fDWnA{@xEOhAWzBUfCEj@?BEn@IfBG|ACzA?BClD@jB?PFvD^bN@FTrIHfC@x@Bv@DvABx@@v@Bx@Bv@FpBDjBFpBFpB@t@HnCDrADbB@LBz@HzBBh@?BDv@J`BNdCPvBFn@@HXlCRdBJt@Hv@Jx@F`@?B@JFd@J~@DZBPVjBZxBd@~CPrAN~@@JThBT`BJv@xApKp@vEj@zDp@rDb@nBf@zBDRf@nBz@lDf@pBH\\FT@@FXv@|CbA~DNr@H\\h@vBPp@Np@r@vCz@jDVfAb@jBz@jDr@tCj@bCDPnExQJ^DPH`@jErQ@F|AnGf@xBz@rDl@fDv@~EBJj@lEh@jFHr@Ft@N~ALpBFdABp@P`DDfAr@|QHlBN~DJ`CF`BFpAPtD@Rl@nPPzELfDd@xLHjBBb@TdHRhFNvDLnDj@rML~CL~CRbGR`FLpCNfELbDf@xMHnBRtEHnBDv@Bx@x@zTF~A@TV|GXhHNbELzCNxCNjCR`CFl@PtAR|AXvB\\`CR|A^jC\\vB?@R|Ap@tEBLj@~Dh@vDb@|C`AnGp@vEJt@Jv@ZrBNdAb@xCn@nEz@jGj@~D`@pCt@fFT~Ad@zCx@|FXrB\\dC^|CR`BJbALpA^jDT`CXlCVrCnB`S~@vJjApLn@pGtArNHv@p@dHhAjL`AxJP`Bv@fIXlCxAlOXlC|AdPpAxMf@fFp@tGhA`L^`EPdBh@hFhAjLXtCTxBLxAHv@Fv@P`BP|A@Nd@zEd@zEHz@~AbP\\dDFv@n@rGNtAd@zEr@lHzAnObB|PpCzX@Nd@xEj@tFv@fI?@JbAXxBRxAVzAVvALp@XlAT|@Pp@^nARn@z@xCdApD|@|CvBnHpAlEd@`Bx@nCv@pCdCrId@|ANr@p@bCn@xBvCbKRp@Tv@Pj@Rn@DJLb@Rn@Pl@Rp@f@|A\\hAFPJ\\|D~M~CpKxBtHt@dCV|@`AdDbAnDpDbMbBvFhA~DjCzI`@pAbCjIvFrRBHPn@pB`H~AtFxDrM~O|i@lAbE|B`IlBrGJZn@zBd@`BrAnEjA~D?@`Urv@jDnLV|@|@~ChBdGdDdLxA`FPl@?@Nh@jBlGn@zBfAtDBF~@bDL`@Rp@pAlEzBvHHXLb@~GtUDLL`@dDfLDL~ApF`@rAv@jCPh@Tn@FRN`@h@rA`@x@@Df@dA^r@^j@Zf@\\h@l@v@`@h@X^`@b@`@b@r@n@@@j@f@n@d@DBZR^TRLPJLHRJVLd@R`@PD@?@\\JRHn@P`@J@@D?r@NvBVD@\\DhBVVDzAPTDD?\\FB?^FjANPB`@FPBNBlEl@NBJ@f@FdBTt@Nf@HJ@\\DpATn@LRDt@PbAVlBx@ZNf@Xv@f@hA|@dAz@PP`@\\Z^Z^\\`@VXX^^j@LRRZr@nAR^h@hADJ^x@Pb@Pd@Tl@Tl@d@xA`@zALb@jArEdAdEPp@Pp@Pl@Pp@Np@Pp@Pp@Pp@Pp@Np@b@bBRt@Nl@Pn@Pp@dAfEHVFXPn@ZnA|@hDBNbAtDxAvF`AxDT|@pA|EXjAv@vCr@pCHZXfAnB|H\\nAnA`FhBfHl@zBz@bDl@dCJb@XhAX|ARnAZnBP|AN~AL~ALhBDjABt@FxB@nB?pAAlBEpBIlBOzCKhBMpBC^i@hJIzA_@hH?B]jGALKpBW~EMpBEv@MnBShDEv@[~EEv@GbAe@~GKnAMxAE^E`@OjAUdBYpBKr@Iv@SxAMhAIt@UlBUjBCXE\\a@nCS|AKv@In@Gh@Eb@AL?FI|@EhAC~@AZ?l@Aj@@fA?\\DpADx@?FFn@Fr@NvAJn@F\\BNX|A\\~A?Bx@bDJ^Lb@HXL`@N`@DLNZJXT`@NZNXp@nA`@t@LVR\\BFLTDHLRT^HNFHBFLRJP\\n@NZFLt@jBZv@Z|@L\\tCbIvBdGZz@N^DLL`@dC`HTl@|AnEHVr@tBr@rBf@vAhBbFb@`A^|@DHTf@@@P^DHTd@Xh@V`@Zj@Xb@Xb@DDNTV\\\\b@`@h@\\`@FHd@h@b@`@d@f@d@d@^Zd@^`@\\n@d@^VhAt@DDpBpAtA`ATPRNJHTR^^^^TXJLX\\BBDHV\\Xb@R\\BD\\n@Zn@\\v@Rf@Pd@L^BJNb@BJPn@Ll@Ld@Jh@BNFXTnALr@DVd@pCHh@v@pEvAjIhBvK^zBVvAh@|Cv@pEh@|CVvAh@dDBHLr@Nx@Lt@Nr@Jn@Nr@Lr@Nt@Lr@DTVpA`@tBF`@DPLt@PdAFb@Jt@@DVvBL|A@BJnAHpAB\\BXDv@LpBDh@TtDBf@ZdFt@bLBb@XtEF`AP`CH~ADv@Fv@?JDj@NnBDh@L|BFv@@XPnCf@nIDv@`@xGB^LfCDx@Dv@BR@b@@HBr@@r@?H?fAA^?LCn@Cd@?LAXI~@Gx@Ir@Kr@Ox@Mp@On@Qp@GRQn@cBpEGRk@zAk@zASl@MXGP]z@M\\EHQd@MTOXS\\CFSXABOPMPCB_@d@UTMJWTwDzCYVEB}@v@_Av@OL]\\MNWVEDUVGHQT[`@INGHSZYd@GJ_@v@_@x@CDSf@GNK\\Un@Sp@Sr@Ol@S|@SfAKl@CXIj@AH?@Ef@MfAEn@El@AL?@Ch@?LCf@Ab@An@An@Ar@?B@p@?F?^@j@@^@XB~@Dp@Dp@Fp@Dh@Fd@Fj@Jt@Ff@Lv@Jh@Jj@@FXdB@BLr@XdB?BLr@?@ZfBLt@Lr@BJ`BjJlB~KjBnKx@bF@Db@~BHb@Lt@Jl@DVFX?@Lr@Jh@BJJl@?BFVDX@@DZFZPt@Ln@Jb@TbAHZFVPt@J^Ld@Rr@Nh@J`@L`@Rt@HVJXPh@?@HVHT@DL^JVn@fB\\`A@BJXFN@DRj@Nb@L\\JZN`@L\\N`@Rf@Pf@DJPd@Rj@@BRl@Tl@DNHRL\\JZJTHTBHBHN`@Pf@Zx@Pf@FPFN@DL^JRPf@Pf@BDNb@@BL\\Pd@p@fBDHBHRh@HTHN@DLZHRNd@Xt@Tj@Tj@Nb@LZb@fAN^BDVr@Vn@Rh@Rf@^`APb@JTBHBFPd@HRN^JZPf@Pj@Rh@\\hAj@dBPd@l@fBVz@Rj@Pd@JXHTN`@n@bBNb@DJ|@bCBFDHHTBHVp@L^N`@Nd@DLDNFPDLRt@Nn@Pt@RbABFTlABP@@Jn@BTDTDTD^BJ?DJp@Hn@?BFd@LlAFn@?@@JFf@Dr@BVB^?D@TBt@Bt@Bb@@x@@T@jABrADpEFvF@v@@p@?FBv@Bz@DnBDpBFpBDpBBx@@v@Bx@JxEJbEHjC@p@?NDvABl@DdAD~@@NBx@Dv@Dz@FjAJnBJrBFpAF|AFxALrC?@@PRzE?FDfA@\\@^J~CBbADpAFnBDpBJtEBhBBlA@d@@b@Bn@@r@@b@@X?ZBf@@d@@`@@X@n@@bA?l@?p@?n@At@Af@?j@ATA\\AVA\\Cp@Ex@C`@?FKrAKvAIr@E^MbAIn@QhAQbAUpAEXG`@GZADKf@Id@Kl@aAfGu@rDUnAe@pCCJk@dDa@dCSdAADYvA_@lB_@|AYhAIXOf@W`Ae@bBe@tAaAtCQl@EHq@vBEHSn@O`@w@bCc@pAk@dBw@|Bm@fBu@|BM^ELOd@Qf@Up@Wv@ABM`@ABc@rACDSj@Sp@ELOb@GR_@fA_@hAQl@ITEJOb@K\\GNm@hBe@rACHM^Qj@[|@Qj@Wt@ADSl@_AlCmAtDa@lAi@`BEJ}@nCu@|B?@EJSl@CFOf@q@nBaAzCgD|Ju@|BCHQh@Qf@Ob@ELK\\M^yAjEe@vAqBdGeA`DWv@Od@MZg@|A}@jCe@vAUr@i@|Ag@|A}@jCaAxCO`@g@|AcAzCM`@u@vBYx@_@`AO^Wj@MZo@rAm@jAc@v@GL_@n@[h@e@r@]b@ILm@x@ORu@z@g@h@Y\\k@h@YVa@`@_@Xk@`@c@\\QLcC`Bk@^yA`AkCfBSLaC`BwClBqH`FSNk`@vWSLaAn@q@d@o@b@cG~Da@VcEnCcAp@GDa@XoBpAOHQL{@j@aBhAmAv@UPe@Ze@ZmAv@i@`@[RWP]TWP[Ry@h@sClB_@Vk@^sA~@{BzAqCjBsA|@w@h@w@f@cEnC_An@_@Va@V?@_@VWNGDcC~A_@V]VsA~@g@^k@`@[Va@^kAbAk@h@YZUTo@n@kApAs@z@qA`B{@hAqCtDq@z@ORg@p@EDWZw@dAgEpFyBtCo@z@qBjC}ApBuFlHILy@bAcC`Dg@n@g@p@cEnF_BrBcArAw@dAaAlA_EjFuAfBUZEDw@dAMNQRGJeAvASVGHSXIJ[^SXGHSVIHQVA@}@jAY^OPIJc@l@[`@ORCBA@GHSV]b@EHSVe@j@CD[`@ORGHYb@q@z@c@j@gCdDEF[^WZEFMNMPUZGFY`@]`@q@~@]`@CD]d@WZsAdBq@z@q@~@y@dAuAfB}C`EgErF{EnGkIrKqFfH[b@Y^}FtHW^sAfB_AnAoA~A?@qBjCmClDUZ}C|Ds@`AoAbB}B|CUZ_BxByAtB[d@[b@?@w@hAq@|@wAtBYb@UZuBxCYd@[b@i@t@{BdDiA~Aa@l@CBOVEFINa@p@[l@CDWh@?@Yn@k@pASj@ITWx@k@lBc@hBsAjFGTaAdEgCnJwBlIQp@Oj@cBnGCJq@|BkBvGgAzDADIX[`A]jAQ`@]z@g@bAi@`Ak@~@i@t@Y^{@bA}@dA_@Z_@\\]\\EDIH}@z@w@n@}A|@mBxAo@f@}@r@_C~B_@^oB|Bg@n@u@bAqAjBk@z@cBpCQXs@pAEH}AnCMRKPcBzCyD`Hy@zAgAjBuAdCg@z@iKzQIREJOXe@t@kAtB{CrFoI`OaBlCgClE_InN_@n@Yf@gAhBu@nAi@v@_ApAe@n@Y\\cAjAu@t@i@f@u@p@iBxAkGzEiCtBqC|BmBhBaB`BgAdA{NbPiBpBoAtAq@z@[^kA~AaAtAa@j@sAxBOVe@x@q@lAmAdCiAbC]z@{@tBq@dBUr@Yv@eAfDCFCFu@hCABOl@_@~Ai@tBkA~EEN}@rDETQp@Qr@]xACHc@nB[`Ba@pCKz@KpAI~@S`DGbAg@xHAVi@nIk@pIYrE]hEQvAAFQhAYzAWbAa@vA[z@_@z@a@x@U`@c@p@Y`@Y`@[\\g@f@e@`@CDy@p@k@d@w@n@k@b@i@d@CBe@`@k@d@i@b@QNWTk@d@w@p@a@\\UPw@t@i@h@u@v@mAxAg@p@}@pAm@dA[n@g@|@_@x@_@x@aArBsAxC_ArBuAvCaBnDs@~AiAfCcAxBQ^uCjGuAxCk@pA}@nBm@hAo@lAm@dAc@n@Y^}@jAu@x@w@t@w@r@i@d@y@n@gA|@cAx@A@y@r@eAz@uAhAgA|@eAz@qBbBqB`BuAjAeAz@_ClBg@`@}@r@gA~@iXzTu@p@cFbEgElDmAdAa@^MLURSREDq@v@q@x@ORUZY`@GHMTe@t@A@S\\Wd@a@v@Wd@A@Sb@i@nAYv@Sj@Ql@Qj@CHENI`@A@?BUbAI\\Mv@AHWzAKv@ERQhAa@jC[vBOhAQhA]vB[xBQrAMz@S`BQjBKbAIfAGv@MxBQvCQvCGjAGjAQvCM~BQvCGhAEt@M~BKbBGlAGp@Gn@Gn@A@Ir@Kn@Kn@Ml@Ml@Oh@k@jBSh@Uf@Ud@Ub@Ud@Y^W`@Y^uD~Ec@l@e@n@e@r@[j@]j@]v@]|@g@tA}@rCgDjKgChIiAlDWx@{@fDMj@QbAKp@SxAShAATKxBEnB?p@AP?Z?B?d@?l@Bl@Br@@PDv@VrCJx@\\xBZrAPr@BNVz@HVBDJZDJFNLZN\\NZZl@T^`@n@X\\Zb@@@\\Z\\\\@@f@f@RP^ZJJp@h@LJt@l@JJlBbBtBjB`DjCbBzAvFxEPNf@b@nB`BtAjA~BrBVT~@v@b@`@xBvBtAxAfC|Cl@z@f@v@t@xA|@tBd@rAf@lBb@nB^jBVnAb@fC\\xBt@lFv@fGb@`Db@dDzAnLrA~J\\~BJt@@@x@|EVjBFj@@JHh@XvBb@`DZ~BLfAT`BHn@Hh@VnB@FRrADTJt@Hj@TnAFb@\\pBX`BDTTrAP|@Z|ANr@DVt@vDl@tC|AvHBPt@tD~@xEf@~BThAnApGd@xBtAzGbA`F`EnSrAvGRbAn@zCl@zCl@xCzB|KVnA`@pBBL\\jBT|ARjBNhBH|@LzBBb@JnBNrCHnABtAR`BV|A`@tBLh@l@xBlAfERn@`@tAdB|FRn@J\\DPFN^nAJ\\?@FN\\jAlA|Dj@pBZjAT|@BL@BH`@DNDLRhA`@fCNpAThBHz@V`DDd@LtCBd@B|@D`D@v@BfC@fCDvFBtB@pABd@Bv@Bl@B^?FDb@Dj@Fd@Hn@?BJr@Hj@BHZhBF\\VtAVxATrADR\\rBP|@\\hBn@pERfBLdAPbBNrBFn@R`DNtCHrBFjBDjB@d@DvC?p@@tD?`D?d@@~B@|@Bx@?HFfB@n@Fr@Dp@PnBHz@@Ln@vEz@nGfAbIzBlP\\lBLr@Hb@VpAd@xBh@xBd@jBj@nBf@~Av@|B|@dClA`Dj@xAdClGbA~BZt@zAxDRh@Xp@dAlCfArCN`@^~@Tl@pA~CtBhFtBjF`B`EbAdC|@|Bh@pAt@hBN^dAlCXp@Th@Tl@Th@?@~@zBp@dBRd@@BbAfCBDz@xBXr@JT~A`ETh@DHb@jAlAzCP`@fArCz@vBvAnDdAjCh@tABFz@xBP`@~@~Bd@lARd@rBjFTh@d@lAjAvClAzCtAjDf@|Af@bBZjALj@Lj@RfAL|@Lr@Fj@^vDJrAHbCBz@@pA@`AArAC|AEdAG|ASpEY~F[tGc@|Ja@`IATWpFSrEEhAUnEIdB[bHMhBKhAMvAQxAOpAWpBKv@mAzJUjBw@tGyBrQcApIwArL]rCg@jEe@pDUdBe@hCS`ACH_@xAe@xA]z@_@z@Yn@a@v@S\\m@~@w@hAkAbBs@dA?@w@fAs@bAwApB}A|BEFKLgEfGuB`DsArBs@hA[h@u@lAw@nA_AzAmB|C[d@oArBAB[f@qAtBOTwA~BEH[f@}BxDc@t@yGxKq@hAYb@q@hAYb@Wb@Yd@q@fA?@mAhBINOR[b@u@fAo@`AQZqFzHwCzDuBbC]`@y@`AY\\_@b@]^]^sCbDA?y@`AiFfGkApAk@n@uB~BoE~E?@uB`CwBdCuA`BeBtByBhDgCxDYd@[d@A?kAjBqHhLU\\A@Y`@{LhQw@jAY`@sAlB[d@w@hAgA~Ae@n@aCjDUZmBtCOT_BxBMPmBrCo@~@q@hA{@~AmAnCqAzCeBpE_@`AcAfCmDxIkArCi@lAy@fBiAzBe@z@UZYb@y@jAk@r@w@dAKNw@x@qBpB{CtCwEpE}BxBk@l@GJ]b@IJA@OTYb@ABk@v@k@|@kCjEoD`GgIvM_HxK]h@kAdB}FjI]`@kCpD[b@w@fAuAhBKNOR[`@?@iBbCc@j@[b@{DpFyB~CiApBy@tBk@dB}@hD[dB[fB[nBKn@SzAu@rEEPo@fE[fBoA|HSlAeAnG_AlGkA`Ha@dCKt@YfBId@]xBSjAG\\YfBMt@SlASnAMt@Mr@Kt@Mr@Mt@?B_@zBu@`FCPYjBGh@M`AE^Gb@g@lEIt@[lCKn@K`AERCTGj@}@lGeAvH[tB_AbGMr@eAjG]jBi@|Ba@xAaBtEGP_A~BqErK[v@O^k@zAEJOb@IV[rAgAlEGZg@|BOp@S|@[vAAB_@fBOr@a@bBa@dB_@jBm@pCq@zCk@fCERQv@WjAs@xCYnAW|@Qj@M`@y@tBk@tAi@tAcA`CyAtDs@hBcAdCqAxCQ`@q@`BA@Uh@gAfC{A~CADmAjCaAxBmCvFYl@}AlDsDxHIPMXsAxCo@zAGNUl@]|@a@jAY~@}@lDc@xBIl@Mt@YnBw@hG?@u@zFmAvJa@nCWtASx@Sz@i@pBo@nBAFQn@c@|AUt@Qn@Sp@e@|Ag@`BMb@EJOh@m@zBWv@]nAw@dDe@zB?B]pBMz@]nCq@~GIl@i@zEOlAE^It@Iv@UlBABIp@In@ADKt@E^GT[bBQt@U~@Mb@A?Sl@CJOb@Uj@Uj@?@m@jA[p@EFU\\Yb@?@[b@o@z@GHA@c@j@STe@n@_AfA}@fAcAnAsBfCaBpBmAxA?@wAdBsA~A?@UXa@h@_@l@Wb@U^Wd@A@wA`DeAlCw@dCU~@_@vAkA~FMx@M|@A@Gh@ANE`@MtAEl@Ex@iAxQo@tGKn@WlBq@|DaAbFk@vC{@tEi@rCo@dDo@jD}BxLS`A{@pEWtAq@nDw@`Eu@jEKh@CRQv@EZOr@EXAFkAbGCP}@|ESjAgAzGaBrKi@fDAFADcCdO_@rBYnB"
                     },
                     "start_location" : {
                        "lat" : 51.0861808,
                        "lng" : -114.21987
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 338
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 51.2649066,
                        "lng" : -115.9313446
                     },
                     "html_instructions" : "Take exit \u003cb\u003e50\u003c/b\u003e for \u003cb\u003eAB-93\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "uj{wHf`qbUGJCFCRId@Kh@YtAc@pBK\\IZITIVIXO`@ELM^Sl@Yv@Qb@i@rAYbA"
                     },
                     "start_location" : {
                        "lat" : 51.26331159999999,
                        "lng" : -115.9272443
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.1 km",
                        "value" : 10085
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 473
                     },
                     "end_location" : {
                        "lat" : 51.2285701,
                        "lng" : -116.0502633
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAB-93 S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ut{wHzyqbUr@fCPp@Pp@BLJb@Pp@H\\DNNr@VdAPp@Ld@FT@@FVJ^J^@FBHPp@J^DPPp@?@Lf@@HFTBPR~@DZDXD`@Db@Db@?BBZ?\\@F@l@?@?v@?@?fBA\\Cd@Ed@Ch@ALGv@ALSzCEj@?BEr@AJANM`Bi@bIGv@Gv@AJMvAQxAUnB]hC?BWvBOjAOlAKp@K|@?@Gl@Gh@CVGj@?BADGv@Gx@Gz@Cr@AJCp@C|@Cz@?@CzAAlA?FCjB?PA`@Al@?x@?FCjAAlAErCIfGKtHQpOG`FCbDAv@?v@ClDAx@Ax@?BA~A?L?R?b@Bh@?P@PDd@?@F\\Jp@BTDTL`@Nf@N`@P\\NXNTJLDDRTBDHFFHLJ`@VVLF@LFRFLDv@TNDRFbAZb@LB@VHDBRFLFNFTNTNDDXR\\^VZNPVb@LRJRRd@@@Rn@HRHZ@BHXJf@H^DV\\hCD^PjAJt@Lt@Jr@?@d@`DVjB@@b@vC`@pC\\`CXnBVdBLt@NbAT|AXlBb@~CBNf@tDd@dDXxBVhBZvBhAxHD\\NdA\\zBp@xEBNFd@p@tEN`AZzB\\dCF`@n@nE`@fC^pB\\xARz@b@xARn@BJb@nA\\~@j@rAP\\Vh@Xj@Tf@^x@\\j@\\l@lA~A~AtBBDf@|@Zv@Nd@BFNx@Jt@HbAFtB@XB|AB|G?Z@|BBxAB|@Fr@Hx@?@Jr@Lt@Nt@Tz@Ld@Pp@J^hAfEBLPp@@D^dBRtAPdB@XDdAHlEBjCDpBFjDHzE@`ADzB?RHjD@z@FtB?b@Bv@@x@DpB?\\@ZBlB@t@@F@f@B`@BZDZB\\H`@F\\Ln@XjAJ^Lb@d@tAL^vB`HpB`GnB|Fp@pB^jAJXd@tAv@|BZx@LZ|@|BDHTh@Vj@Td@@DVh@Xh@BFR^r@pAXf@PZ|D`HXd@lAvBXf@r@lA~BdEn@dAt@pABFjAxBb@~@Th@N^fA`DfAxCPb@P^R\\`@p@\\d@LLHJPRFDVXDDVT|@x@DDXT\\\\b@^XZb@f@n@x@`BxBPVZb@l@z@HLXb@PVHLv@fAJPlAnBj@|@n@`AbAjBLVNTHPr@nA@BlArBhApBh@~@lApBp@dARTPTRTRR`@\\LJRLXRTLNHd@R^LD@XHp@N\\HXD~@LZDF@d@Hh@J|@JD?j@L@@\\HD@NDTH`@N\\T^X"
                     },
                     "start_location" : {
                        "lat" : 51.2649066,
                        "lng" : -115.9313446
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "93.9 km",
                        "value" : 93899
                     },
                     "duration" : {
                        "text" : "1 hour 7 mins",
                        "value" : 4003
                     },
                     "end_location" : {
                        "lat" : 50.6224068,
                        "lng" : -116.0715199
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eBC-93 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering British Columbia\u003c/div\u003e",
                     "polyline" : {
                        "points" : "qqtwHbaicU\\XVTh@l@`@j@l@|@V^BDXd@r@nAXd@Xd@FJRZZh@j@`Ax@vAhCfEvAbC^n@RZFHlBpCZd@@@X`@h@t@LPZb@v@fAnBlCv@fAZb@v@fAd@l@fBbCdEvFvAnB|C`ERVbAjAxAbBl@n@`@f@\\^\\^vA`B\\^l@p@j@n@PPJL\\^Z`@DDpA|A@BX^\\`@@BX^Xb@?@Zd@z@pAxBpDDFhBxCPXFJnAtBrB`DZd@Xd@Zd@Xb@Zd@HNj@|@Xd@?@d@v@b@v@Td@DHJT^|@Rl@@DP`@BJRv@d@xAPl@?@f@~ARn@DLt@`CNf@BFh@zABFPb@FNVj@NXR\\`@l@@Bp@z@VXTTTN^XhAv@rA|@rA|@XTVTRTTTZ`@RZX`@h@dAj@lA|ApDd@fA\\z@Vj@vBhFjAtCjAtC@BRf@Vj@L\\v@fBRl@Lb@Rp@Nn@BLH\\DTJj@@FNz@RxAj@jEBVJt@F`@Hf@Rz@V~@Vt@FNLTVb@Xb@DFX^BBZ`@hAvAJLjAzA^h@DFR\\|@`B`@z@HPl@tA?@Tj@Pb@t@bBf@nAVh@@DTd@BBVh@Rb@BDp@pABDnAvBl@bA^n@V^LR~A|BPXd@n@t@fA@@X`@V^BD`@n@Xd@PZ^p@Vh@Rb@f@nAZt@Tj@f@nAp@bBN`@DJRh@L^Pj@ZdAPr@^fB`@lBJj@Lj@@FNp@BJLd@BHNd@FRTp@\\~@BD`@bAHRVj@j@xAl@vADJP^Tj@Vl@l@vATj@N\\^v@Vh@FNf@bAp@rANZFLXh@Vh@Vf@T`@lAdC~@nBP`@L\\Xp@f@zAFPHXNl@@FFVDNHb@BHVrAFf@DV@DXdC?BJt@Hv@Jt@^nDp@rGHf@Jl@Nh@Nb@L\\Rd@R^BFPP\\`@f@f@l@l@ZX~@~@d@d@rAnA@BDBl@l@j@l@ZZ\\^PT\\d@T^Vb@Xd@DJLTJRDJf@hATl@Vj@d@fAXn@\\n@Zf@T^^j@@BX`@FHjA`BDHfBfCPVd@p@v@fA\\h@V^v@fATZDFZd@d@n@PVb@n@l@|@n@|@b@n@Zb@HJNXf@x@Vd@Zj@b@~@x@jBl@xAv@bBZn@^t@PZJT`@p@`@j@Zb@LPj@t@x@~@JLPP\\^FFr@v@VZBBXZBBX^b@l@f@t@\\p@BFNZTj@FNHTL^L`@@DHVHVJ\\Rr@DNRp@Pl@FPJ\\Pn@Rl@@@Pd@d@bAHP^t@v@`BFJXl@j@jAHLb@z@lAdCp@rAd@`AVf@?@Vh@`@z@b@~@`@t@l@nATb@LTDD^l@PXZ^PRXXXVTPTNTPB@RLJFNFJF^NZJNDHBXFv@Nt@LdAPhBX^Fr@LpCb@bAN|B^^FB@nDj@xEt@bANhBZjBX`@HpDj@b@F`En@~Ex@F?hBX`Df@x@L`@Bf@@b@A^Cf@Ed@I`@KZITIj@UDA`@QhAe@xAq@FC`CcAfCgA`@QtB{@zCsAf@S^QTKFC\\QBA\\SXSTQTQPOZ[VYPUBEZa@V_@BER_@r@sAh@aA^w@hAyB@ChA{BXg@n@sALSvAoCxBiE@Cf@aAJMJSLQJQb@o@FGZc@?A`@g@VYLONO\\]vB}Bz@}@zA{AxA}Az@}@xF_GlDuDZ_@NQLOj@w@`@m@d@w@`@s@`@w@Xm@JSz@kBn@sAfA_CLWxCuG\\w@f@eAXs@`@cA?AXu@Ng@FS\\kADOn@eCvAyFb@cB`@cBt@uCNq@Pq@Pq@Pq@`@cBPq@r@uCdAgEPq@Pq@@EJ_@Lc@HWHUHW@CL[Vg@FMDINWBENYJKDIRWHKJKHGJKVWVS@A^WHEVQ\\U`@Y`@WDCXUXUDETUFGPQJMLOLOJK^i@Xc@`@o@\\o@@CNYFOFMN[?CP_@BIZy@Rm@Lc@DKLc@J_@DOd@cBBKLc@Rq@Po@Po@DKLe@Ro@J_@Nc@JY?ATk@LWLYP]Tc@DGLSV_@PUBETY@ATWVY~@aAHIf@g@b@g@b@e@`@e@BCPUHKJQPWNW^q@@AVg@@AXo@Rc@DMh@mARi@P_@DKj@wABERe@JW`@aATk@FMVo@Z{@DKRi@Tu@?AV{@T{@R{@BONs@Ns@T}@Je@@ANo@@CPk@La@Rm@Pg@HSHOL[\\s@rBiEHQf@gA\\s@Vo@JYL]FQNi@L_@H_@Je@He@Ji@F_@Fi@Hi@Hy@JkAHu@@SHy@F_@De@BQBQDY@IBOJa@Hc@Lg@Lc@Rm@JYDIFOLW@CLUHQBELSHMXc@@AR[RWNQv@eA\\a@Za@Zc@\\a@Za@x@eAZa@Zc@V[jEyFV[^k@LOdA_BR[dAaBtAyBJOZe@nAqBnDuFx@sAhDmFzBmD~@yAZg@z@qAT]nAqBT_@^k@NWvBeDt@kAnAoBZe@?At@iAR]z@sAHOfAaBXe@z@sAR]pAqBHMNWf@u@zAmCrAkCnAgCHMVi@zBmER_@lBwDvBeEhA{Bp@qAh@gAf@_AP]R[DIXc@PWT[\\c@d@i@h@e@ZY`@[l@e@PKrA_AnEaD^Yj@a@rAaA`@W`As@~BaB~@q@`@[\\WdAu@z@o@JIz@w@RSTUl@o@TW\\a@fAmAdCwCvAcBTWFGtBaCx@aA\\a@VYb@e@Za@\\_@pCcDvBcCvAcB\\_@t@{@zAgB|EyF\\_@T]RYNUNU^o@BGXg@@Cb@aA\\_AbAuCb@sANc@h@{Az@eCFQRm@Tm@BIj@cBr@sBBEVo@Vg@BGVi@R_@b@s@\\g@^g@h@o@@AZ[BCf@i@jCeCNONM\\]|@{@`AaApAoABC^]r@s@FG~C{CVWb@c@\\_@x@}@^e@X]`@o@`@o@~@yA\\k@dBsCZe@Xe@`@o@bBoCFMj@_A`@m@l@eAZe@PY|@wAXg@fBuCrCqEh@{@Xg@z@sAbBqCvA{BjAqBp@eAd@u@NUp@iA@AZe@t@kAXe@PYb@q@Zc@?AdA{Ar@_AdAwA^g@Zc@\\c@NSJOZa@Zc@Zc@X_@@CZa@Zc@h@s@j@w@Za@Zc@NSJOrAiBZc@Zc@r@_A`@i@Zc@Zc@v@eAZc@Zc@v@gAZa@RYd@m@Za@Zc@BEV[NQLOLQNM\\]l@g@dAm@LI\\OBAf@Qn@Ot@KhBYb@GdAQnC_@dAOb@Gb@ID?\\GdAOb@Gb@GfAOdAMfAOdAOjBU\\EDAbAUb@M@?`@OHCd@UPMNIPMDEVUNKNQPSJKX_@@AZc@lBmC@AZc@Xe@v@iAZc@JO`BcCpAmBZe@rAqB`DyEv@gAv@iAt@iAZe@t@gAZe@pAmBZc@n@_AFInC{DhBiCZc@tAkBpAqBhAqBtAsCd@_AVi@Xk@b@u@NUTa@BCZc@Zc@TYd@e@|@{@RUbBeBPSh@k@?AZa@V]t@iABGXe@nEqH\\k@tC{E|@yAXe@zCeFBAXg@Xe@bG}JBEXg@t@mAXe@Xg@nAsBlAsBdDsFjAyBP]Zq@Rc@nAsCdBqEfByE`@wADQZqAp@{D^{BTkAFYf@_BHU^eA~@kB~AaDTm@Tk@j@{A`AeCTm@`@cAVq@z@eC\\s@j@iAnAkB`AeAXWf@_@`@WLGx@a@bA_@FCtAc@j@S~Am@|Ag@jC_ANGtBu@bA_@NEvAe@b@O@A^KfBm@zAg@pAc@`@O`@OB?`A]`@Ob@M`@Od@Q`A[`@ONGPGb@Q@?`A_@@AhB{@ZQ^SbAk@FEVO`@Ub@W~A_A`@U`BaAd@Wz@i@hC}A|@k@`@W`Ak@^WBA\\S^W`Ao@^W^W`@UjD_C`As@RS^]Za@@APUFI`@m@R_@Vi@BIj@oAl@sAJUJSn@sAZk@Ve@h@y@n@u@p@o@n@g@v@c@^Wn@_@PKb@U~@g@`@UNIrAw@`@W@AZUl@e@PO^]POh@k@@CZ[zA{AxA{ATUf@e@\\_@xC{CZ[z@}@\\]v@y@`AaA@AZ[xA}Ax@y@DE|@y@lA_Ap@e@\\S`@UHEVMdFmCfAm@`Ai@`@Ub@UxEkCvGoD`@S|@g@vJmF~A{@`@U`Ai@`@SLIRIbAg@|@c@`Bu@JE^O`@Q`@Q`@Q\\OBA`@Q`@QlDyA`Aa@dBu@`@QzAo@nAg@l@WxAq@`@Q@AbBo@rAg@zBu@jC{@pFiBdA]`@M`@OdA[b@OpFkBNEPI|@YFCrA]REZGj@EBAx@AH@b@BN@RBb@Fn@Pb@NRHb@Rl@\\PJFDv@n@JFRP|@t@~@v@^XXVDB\\Zh@d@RRj@f@vApA|BnB^Z|@v@^Z\\Z\\X@@^Z\\\\lC~Bl@f@ZXB@l@l@NHZTVNLFHDTJZLFBVH^F\\Df@Fv@B^?r@@R@b@?F?x@Bf@DZFH@\\HZHJBRFb@LLDRHLD`@Nb@N`@N@?^Nr@VPDBBZJ@@ZJDBNHZL\\Td@ZRRPRHJ\\`@BBTb@HNd@bAFNb@hA\\`AJX|@lCPd@d@pAFPHRN^j@hA@@n@`A^l@Zd@HLNVV\\BDZb@BBX\\JN`@\\NHXRf@X^N@?\\J`@Hn@F\\@fAFD?`A?l@@X@V?j@FB@d@FXHD@d@Pj@ZRLHFf@b@JJNNLNLPT\\PXXf@FL`AnBJRJRVh@bBfDdAtBBDVh@BDPd@JZFRRn@@FNh@Lf@@HNr@Hd@`@|BTbBDZFXNz@\\|A?@Pn@@BNf@?BNf@BFTl@Tj@Th@@@v@dBLXj@lAZp@R`@h@lA^|@?@Rl@Nd@BHNj@?DNl@@BRbAHb@DXDZFj@NxAFrADxA@lC?B?lBAv@?R?d@?x@?v@?R?d@A|@@z@B~@DnAHhA@NLlABLJt@Lr@FVVnADNL^FT^fAPd@Rh@DHVh@b@v@fBdCFH\\^DHTTXX^\\b@^BBv@j@B@bAh@FD`@Rx@^b@PNFPHbA`@FBXLDBZPLHl@^VNLLHFd@f@JJZb@Z`@@@Xb@@BVb@FJPXLTJPVh@p@pAj@dA`BxCHPr@nADHRZt@jANTJNZb@Xd@V^BBZd@Xb@@@Xb@Zd@DFRZt@fA@@p@`Az@pAfA`BzAxBt@jAXd@v@hAl@x@HLt@hAb@p@l@|@`@n@RXZb@Zb@TZDFRTf@h@p@d@LJx@f@~@d@JFrB`Aj@Zl@^ZV\\X@?XVVXV^\\d@RXVd@^v@HPZp@b@nA@BTl@h@|ARl@h@zAFNL\\f@tAXp@@BTd@DHl@bADHn@t@^`@^^HHr@n@|@v@~@x@j@f@PN^Z|@v@RRn@l@b@l@d@p@RZRb@LVv@bBf@`Ad@z@f@p@@DRTHJPTHHTVHF\\Z\\\\^\\|@x@DDVVr@r@FF`@b@`@d@RX^h@V^^j@T^b@t@LXXf@FLf@dAf@rABDTj@Pb@BHRn@l@lBrAlErCnJ`@rAL`@Xz@?BRh@BFPb@JTJTHNT^Zh@RVFFTXPPJLbChCn@p@JJPRVVX\\FHVZDDTZNRLT@BNXJXNd@?@Np@BHJf@BNHr@Dh@BNBf@@ZBbA@dCBhD?x@@pB@v@@pB@x@@pB@v@@~BB~BBtA@T@b@@\\Ft@DXBTHl@Jd@@HLf@@FPf@?@Tj@Zr@T\\?@V\\BBZ\\@@RTn@f@XR~@p@JHRLhAv@RJTJb@PVHLBTD@@`@DB?`@@^Ab@EHAXE@A`@G@A^O?Ar@e@f@]BEXWDEp@y@xBsCx@cAZc@tAgBtAgBPUHKtAeBZc@BCX]@AX[^_@@A\\WFEd@W|@]^Ib@G^AD?\\?T?L@F?VBB@j@Pn@ZHD`@THDTN`@TNHp@b@^V`C|ATLv@^VH\\NB?b@JF@f@HV@N@zA@fA@fA@H?X@Z@D@b@Hp@TRH\\PB@XR^\\j@l@RVNRHNJPLTDHP\\Pb@n@pBhAdDzD`LTl@Rl@x@`Cl@fBnAtDVr@Rl@FNNZJXZj@HHPXHHJJTPVN`@NF@NDPDD?\\@N?l@G^Mj@_@j@m@j@s@@CZ]Z_@RSJILIPMPIXKf@K^Cd@Df@JPFB@PJPJTT@@VVXb@PXXj@JVTh@Vj@Vj@Pb@BFVj@Tj@Vj@Tj@Vh@Tj@|@rB`@v@LVHNZd@DDt@x@ZXVRVPd@Tf@Rp@PnAXPDj@RFB^R^X@@XZX\\DFVd@@@Tf@@@Rh@nAhDFNJZHNHPLVDFZh@V\\^`@`@^`@X`@Tv@Zf@JXDb@B`@B`@Cd@GTEfC{@|CqApAg@lEcBb@OvEiBv@]@Ad@Wz@m@ROJI\\]@Ad@g@l@{@^m@l@iAP_@t@_Bx@gBlB_EVk@Vi@Vi@Vi@n@sADIR_@Ve@?Af@}@l@}@j@y@lA_Bh@o@V]`@c@\\_@\\a@\\_@@A~CwDr@}@v@iAh@{@t@mAHObAcBlAuBXe@Zg@fB{ClAsBjAqBhGkKlAsBXg@r@kArA{BvA{BnAeBl@w@^c@\\a@t@}@bBeB`B}Ar@m@@AZWl@e@r@g@PMlAy@`@W?AbDqB`BeA`@U`C{Ad@[hEoCVO^WjBoArDqC`@]\\[zCkC^[|AuAf@c@pFwE\\[bCsBjAcAh@_@BA`@W`@M^O@?`AYn@KXC^EjAEnCMb@AbI]fH[bU{@~H]zSy@LAjBGb@CfAEvEQjBGTA~DQb@CjQu@VApAIx@Ib@G`@Gn@Mz@YlAa@|@a@bBu@|Aq@bEeBbAc@lB}@|Ao@`@QJETKdBw@dAe@^OZKZK^Kd@I^Gn@Gh@EJAn@AJ?f@@^BT@LB\\Df@JH@x@RfA^bAb@B@`A\\DBZHZJF@l@LVDL@T@TBL?\\BDAb@?B?r@GNCXC^Il@U~@c@XQVO\\Wf@c@h@i@jKkKLKbGcGzC{CX[^]|C}Ct@u@\\_@j@i@lAmA\\]rFsFzAyA\\_@z@{@vDuD\\]z@}@LKn@o@XYBA^]VWDC~@k@@A`@QNIf@SJC`AUvDe@hBUxASPCdAOVEJCVEt@UXK@?^S`@UFEf@_@`@_@r@y@d@m@^m@h@aAJSbA{B@CdA_Cb@}@LWBERa@Xe@f@o@n@{@d@c@TQ^YPMLI`@WfG_E`BiAz@s@p@o@f@m@Za@fGiH|AiBjBaC\\a@dGwH`AsAf@q@\\k@Ve@DIp@{AXq@Vs@`@qA\\oAd@aBd@_Bb@aBd@aBPo@zDeNJ_@DQ~AsFPm@Rm@@EZ}@n@kBBI`@cAjAoCvA_DvBsEVi@n@sAh@kA\\q@fA_CfA}BVi@Xi@Vi@tBoEdFqKLWVi@~AgDxE{JfA}BfHcO|KoUxCeGxCkGVi@n@sAn@uAzDgIlAgCVi@fDgHpCuFn@kA^q@Va@Zc@h@u@~@iAb@g@@Af@e@zA{A^]b@c@~@{@xB}B~CuCrEqEzAyAxGsGrGoG\\]lHiHxEsEpGkGvGqGrAqAp@q@j@o@FIr@aA~@_Bh@eATg@Tm@b@mARs@Ro@Pi@x@qC`@uAf@sAf@qA^w@d@}@^m@t@iAdA_BvBgDrBaDl@aAx@oAd@o@X]X[d@c@XWVQj@_@dAm@VQfAo@bBcAbBeA|FkDHEhDuBvBgAj@WTKJCZKb@Mn@OZGl@Mr@KpAM`@Cv@EnAG`@Gj@Kb@MVKp@Y^UZSLGVUVSbAcAr@u@TQr@{@h@o@\\e@Ze@PYFKt@sAZk@|@aBlAcClCcFjHiNjDmGR]Zk@NUT[RWHILMNQX[d@a@x@m@dAq@bDqB^WbBcAx@g@FE`BcAdF_D`@W~@k@n@a@|A}@t@a@PKn@W\\Kf@I`@GVCXCVA\\?Z@@?`@BZBF@b@FB@h@Lf@PPH`@N?@`@Px@^hAf@B?|@XF@ZHD@`@H^BV@~@?|@Gb@EDAj@Mt@U`@S`@QHEVOJETM`Ak@BCXM@AXOFCLGRIFATIRETGJCTEzGkAfAQHCVEb@Gb@IdAQ`AQxEw@p@K`@EVABAb@A^?F?Z@R?NBdAJrAL~ARPBr@Fb@DVBJ?T@h@?h@C`@E`ASn@Sl@UPK^Uf@[XU`@]b@c@TUfBgBn@o@nBsBvB{B\\_@\\_@nBsBRUbBeBl@m@XY^_@TSzAyAn@m@n@k@h@a@`@UXO`@QZKz@UHAPCh@I\\EPANAR?T?f@@l@Fn@Nx@R`@JjCn@RDNDb@J`@Lb@Jx@Tp@Pt@LL@b@D@?z@BX?P?J?^ERCFANCxAWtDq@lDo@x@On@MTGb@M`@KHCbBk@rB_An@]x@a@dAm@DC`@UDCXO`@Up@Wh@O`@GZAV?`@BR?r@Db@BD?^?^C@?`@KJCl@]FGVWDGVYT_@HMXg@Ta@BCXg@\\c@TUZ[HGNKNKFEXODCd@Ut@WdAYBAdAYNExAUBA^A\\CD?b@CXA~@@P@l@BX?b@AN?`AIXGd@K`AYHCXIp@SPG`AWn@Sz@[^Md@O`@M|@[h@SRILGd@S\\UXQd@]`@W~@s@LKn@g@^[~@u@XUd@]^W~AkA@A\\W~@s@TQx@o@pA}@XSZQ|@c@NI`@St@]n@[p@[^MTELCT?NAR?VBH@NBNFPFRLVN`@\\DB\\\\^b@LPHNBDRd@DJJZJ`@FT@JJf@?BJt@PlA|@hGJt@r@~EHz@DxAAdAAh@E\\E^Kp@Kv@OhAE`@AHEj@?@Cx@?F@n@?N@f@@HF~@Hf@Jf@J^HZNb@@DN\\Xv@@BLf@Lj@Hh@J`ABb@Bh@?Z?b@A~@?f@AJA|@Ad@?P?f@AP@d@?N?`@@`@@\\@J@h@?d@?j@A`@?LGv@Gf@?BKn@AJWvAo@~CMr@CHWvAMr@Mx@Kt@CJG`ACfA?P@p@?DDz@J|@Jf@DVHXHVXv@j@lAHR|@tBDLPh@@DPv@Nx@HfA@X@X?n@C`AE`ACRObBSvB[bDSjBIv@]lD[lCO~@Il@k@vCc@lBIb@s@bCw@tBi@zASl@Qd@[x@Sp@St@Kd@ENGb@CNOhAi@~EAHIv@[xC?HOvACRC`@ATAPAd@?D?h@?H?X@\\?F@n@Dn@?HBh@JbAFv@XlDBTBd@FbA@hA?zA@bAAnA?Z?Z?v@@l@FrADr@Hp@Jx@Ff@Jd@Lh@Rp@Nj@f@dBPh@Rt@Rn@Np@FTP`ANbA@@LlA@\\HhABd@HnB@RNrCPxCFv@JnBJnBPlCBt@@Z?b@?R?p@?DA`@AVATGz@CZIt@OvAAb@?V?P?X@L@RBb@Db@BPBHH^JXLX@DLVFJJNPTTXPNTN^JD@\\Db@Fb@F`@F@?x@Nh@PB?`@N^R\\TBB\\TB@ZV@BVT\\^DH\\l@T`@LVHNHTJVJ\\FNRn@BF`@`B^zAXjAHVPn@^tA^fAN\\Pf@BDTj@Tj@Vj@@DTb@r@~ARZXf@p@dA|BbDl@t@TXFD\\`@x@~@z@~@\\`@Z^z@~@\\^x@`AbCnCf@l@l@l@|@v@h@^j@Zp@Vl@Rl@J`BVF@b@Fb@F`@Fb@FfAN~HfAdJnAfBXH@zA^v@Tp@TfAb@PHp@Z^RD@ZR`@Tp@`@l@d@^X`Ap@^X~@p@~@r@\\V@@~BdB~BfB^V~@r@~@r@^XTNlA`Ax@z@Z^LPLNv@fAv@fAZb@Zb@Xb@LPLPZb@Zb@v@fAZb@b@l@PZb@t@\\j@Xp@Pl@Ll@NbA@J@TD`@H~ADfADv@FxANdCNjCHpA@NFz@Db@FZHb@HZN`@P^PZDJV^PXLXLXPb@H\\Hd@Hh@JjAJ`ABNBVF\\@@H`@BLFTNn@JZPp@H\\Rt@Hb@Jp@BT@LD\\Fz@DlA?HDdBB|AFbCFhD@`@F~D@x@?LAh@?LAnAEnB@v@Bt@@VBv@FpA?\\Br@?BAx@?LAf@?@Aj@K`AC`@ATEv@Ev@Ex@Av@Av@A`B?~B?x@?zA@vH?tB@tCHvB?FHzA@JHjARpALv@?@Lr@DLV|@XbAHXHTRl@\\`AH\\J^Tz@Lz@D\\BVFt@@FBn@JnB@PBf@Bv@Dv@HnBDv@L|Cb@~KV~FFvABn@BnAAxAAf@Al@KbDGrBWvGGjB?^?d@@t@Bl@?FDt@Fn@@LFf@BRPrAp@fE@DBPT`BJj@@FFb@@F@HLh@?DLl@BJ@BJj@Lh@?BPj@BFJ\\Xv@Rj@?@Xr@L\\BFBDZp@R`@NTDH@?Xb@Zb@v@fAPXb@l@@@X`@?@X^@@?@\\`@Z`@BDT^Zb@FHP\\DDLVBHDLFTBL@?DPF^?@DZDVBHJj@Lp@@JJf@Lr@Ht@@JBj@@r@@BBv@?@@`@@T?X?BBX?JDj@@JFh@?@Hr@FRLr@Np@Nr@Np@n@xCDTJj@@FJn@?BJt@BXB\\@PBd@@R@b@?V?^@x@?L?p@?D?v@@x@?v@?v@BlB?NBv@?V@^@r@?DFxB@l@?^AV?VCZABEd@G`@Gb@ERKz@Cb@?@Ch@@J?b@BR?HFZBLDXHVHTLTVh@DHP^Vh@BDFJFNBFBDFTDRDTBT@H@R@d@?`BA`B?TAb@?\\?X?R@b@@NBf@@LFh@@HJh@^bBH^FPL^DLRn@BLTv@F\\H`@BPHn@?DFv@Dv@?J?j@@HAl@?R@d@?J@j@@JDj@?HFh@?@F^DRPp@DPJ^Jb@BLJl@?DF\\@X@HAj@?@Ct@A@C\\CXAPA^ADAX?X?B?\\?X?@@t@@x@?BAfA?b@An@?HCn@?@Ev@?DCp@?L?h@?P?d@?@@TBN@N@BBNFX@DDNL^JZDPPl@@@Np@BHJh@Lr@BNFd@Hf@BJDPBNFN?BHLJLBB`@TRJJJBBHNJTFRFV@B@HBT@PFtB@r@@B@XBP?BBRDPBNDLJZBHDL@BHTDPH\\BFBJVfABHD`@BT@HHb@@BNr@Np@Nr@FXFVHXFTPl@@BFVFZDVHXDVFT?DFVFT?BBJDJHVHTN\\FJJTJRHPJR\\f@@BJLBDVXXZBBNLNLBBJHNJNL^XNJNLNJb@\\JHLH@@@@LFHDD@RFLDP@@@N@ZBF?@?P?P?X?r@Bh@NB@NHJFDBZTPP@@LLNLJJBBh@l@@@LPZ\\h@r@@@FFj@`A@@JRLPp@jA@@JRf@x@Xf@LPNRX`@?@Z^Z\\@@ZZ@@PPj@f@LLDDXVLLNN\\^TTHHJNHP?T?D?BHp@"
                     },
                     "start_location" : {
                        "lat" : 51.2285701,
                        "lng" : -116.0502633
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 235
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 50.62070430000001,
                        "lng" : -116.0709173
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eBC-93\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-95\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "ae~sH~emcUAH?HAF@J@H@HBHBHBBBBDBFBD?F?FADCBCDGDKBK`@U^WHEPKLKTWTKXMrAo@"
                     },
                     "start_location" : {
                        "lat" : 50.6224068,
                        "lng" : -116.0715199
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 187
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 50.620042,
                        "lng" : -116.0733609
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSt Joseph St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kz}sHfbmcUNx@ZhBHb@Jj@ZfBLr@VvA"
                     },
                     "start_location" : {
                        "lat" : 50.62070430000001,
                        "lng" : -116.0709173
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "221 km",
                  "value" : 220984
               },
               "duration" : {
                  "text" : "2 hours 21 mins",
                  "value" : 8449
               },
               "end_address" : "Fernie, BC, Canada",
               "end_location" : {
                  "lat" : 49.5040082,
                  "lng" : -115.0628236
               },
               "start_address" : "Radium Hot Springs, BC, Canada",
               "start_location" : {
                  "lat" : 50.620042,
                  "lng" : -116.0733609
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 187
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 50.62070430000001,
                        "lng" : -116.0709173
                     },
                     "html_instructions" : "Head \u003cb\u003enortheast\u003c/b\u003e on \u003cb\u003eSt Joseph St\u003c/b\u003e toward \u003cb\u003eMain St W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gv}sHnqmcUWwAMs@[gBKk@Ic@[iBOy@"
                     },
                     "start_location" : {
                        "lat" : 50.620042,
                        "lng" : -116.0733609
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "102 km",
                        "value" : 102426
                     },
                     "duration" : {
                        "text" : "1 hour 4 mins",
                        "value" : 3834
                     },
                     "end_location" : {
                        "lat" : 49.81043220000001,
                        "lng" : -115.76881
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBC-93 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-95 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kz}sHfbmcUXQnHaEnBs@pBo@PEPGNGHCFCb@MNEr@S@A`@KjCq@xC}@dAYxAa@FArAe@vAi@v@a@`BeAfA{@RS|BsBxFwFRS`AaADGPODE`A}@jA_AhA{@j@e@jAw@t@g@r@c@v@g@zCoBp@e@^UTOhCaBfAs@~@m@xBuAjBkAVQFE^UtBoANIbAi@h@UxAm@p@Sx@UdAY`AWBAPElA[FChBg@BAXM`@QBA`@QNIh@]d@_@?Ar@s@FId@m@RWHMd@w@@AVk@@ATg@BIPc@@CPi@Ro@FUHYH[DUF]FUHe@n@gDJe@BMLs@Ls@dAcG`@{BZsANs@Nq@f@_BBIRo@Zw@P_@Vi@DIP]HMHODGXg@PY^c@DG@AZ_@Za@DCb@c@f@c@b@[z@m@x@g@@Ar@c@^U`@UlAu@h@[JIJGt@c@j@_@bCyA\\UxAy@`Am@lDuBfEkCdC{A`Am@dDqB`@U`Ak@^WHEVO`BaAdDoBbCyAhC_Bz@i@PK|BwAl@_@h@[@AtAu@j@_@RKz@c@l@[fEyBxGgDz@g@B?`@UjBaAr@a@hAk@j@Y|Ay@hAk@`@QLIRIdCoA`@S`Ag@rKoFr@]rCyAbAi@dEyB^SpAo@l@[JEn@[tAk@zAm@v@Yt@W`A[p@Mn@MdCc@fC[~ASj@Gb@EVCJAzAOdBSpAQj@IRCNEb@I~@Qh@Mt@Qp@Sj@QXIlA_@bBs@~Au@j@Yj@[zHkE~A{@n@a@JGbBaA`Ag@d@Wd@UZQn@Yh@QXKn@STIh@OzAe@RIRIz@a@^S|@i@fAq@l@a@bCaBXSd@]^]d@c@b@c@RWTY^e@HKPWhA}A`AsAV[BEZc@bEuFdCgDFIZc@j@u@lBiChA_Br@mA`@s@f@iAh@oATk@Tk@r@gBZy@N]Xw@f@qAd@iA?AN_@Xs@LY\\q@Zk@DKf@w@f@k@`AeAZUROPKRMHEJGLGLGXKBAh@SVG`@Ox@WbAU\\I^KREVIj@OJE`AUx@WvAc@tAc@f@OpA[x@UfAWdFkA`B]nAWpE{@~Dw@r@M`Eu@l@KzAWrASxB_@h@I`BYlDm@~G}@`GcAjDo@pEu@vEs@nDk@t@KdASv@SbAYRIdA_@d@Uf@Wf@WDCZQh@a@b@[d@_@NQb@a@`AgAlB}Bx@y@h@m@h@q@r@}@h@g@vAmAd@[DE\\Uh@]l@[h@YfCeAj@W\\M`@On@UtAg@b@QrH{CVKHEVKHCjGgCxDyAJGjBs@|L{E`@QtAi@r@YhDsAPINGfCaATKdBs@XK~B_AdCaAn@WrCiAdG}B`A]zB}@r@W`@Ql@UZKbA]rAa@fAYbAQ`BQz@In@GVA\\AdCKx@CvAAxA@nA@v@F|CTbCVlLpAhKfAv@Hp@@bAA~AGj@Ar@Cp@Mn@K|A_@j@O|Ag@jCy@`@M`Cw@HC`@OtCcAvIoClEuA`Bg@xAe@lDiAjCw@`@MVIVGXKl@UPKVK^Qf@W`@WFEfAq@VSXUXW\\[t@s@f@k@f@q@j@u@lIuMZe@hByChBwCtCiEfCcDV]rAgB`AoAPYnAqBnAqBzIkNtBiDb@u@f@}@^m@p@gA^m@^m@NSh@}@hA{BVi@f@eAhFsKtEsHzA{BjDwFp@eAnAoBpFeJ~EqHhAiBjCmD`HqIpW_YJMjBoB~FmGhFuFPS~LuM\\_@h@k@dEoEJKdCmCxB}BdDkDj@o@JMPQJKx@}@vAeBx@cApBqCjCcEdByCP_@N[FM~BaFxD{KxB{GRm@j@iBfEuM`A}Cp@oBlBcG\\cA`BkFLa@jAgD`@kAZy@f@kAb@aAVm@Xi@Xk@n@gA|AgCZc@@AX_@Za@\\a@NSnAsAdAaAnAiAtBeB|OkM^[d@_@~JcITQ|FuEbDkCzTqQxKaJ~BkB|BiB^[ne@w_@^[^Y|DaD^Y^[zD_D^[zLwJzE{D^Y|BkB~@u@zHkG|DaD~AoAzFwE^YzIgH|DaDvRwO^[|AoA^Y^[|CeC^Y|AqA^Y^YzGqF|FwE^YzFwE~AoArC}BpGgF|HmGn@i@lCwBtDyCdA{@zHmGzGqFzIgH@AzFqENMtJ_I\\YjSmPbCoBxFwEf@_@~BiBz@s@@AnCkBVQdBgAx@a@`Bw@hAg@tAi@~@]`Be@rA]jAYpB]lCe@r@Mx]uF~HqAzGiAlMwB`BYtEu@~@OvCe@dBWjC[~AIdAGtEQR?N?bAAhBDp@@d@B`ADfAJpALPBbAJVDfAPhC`@x@NXH`B`@v@Rv@VLDv@VND`DnAtAj@HD`@Rn@ZtAr@bB`ArA|@pClBZV^XjA~@fB|APNlBjBHJ|@bA\\^lArAzBvCJNLLjAvAx@`AtAdBZ^pA|A|@jAp@v@l@v@vAbBJJLNj@p@PT\\`@Z`@x@bAfBvBrBdCJLPRxCrDh@n@h@p@Z^t@~@V\\Z`@FJl@z@DDd@r@HNZf@Vf@Vd@@@Vf@hAzBv@dBZv@FN~@dCL\\FN^hAPl@l@xBNn@`@`BBJVdABPP|@f@lCb@tCLz@b@~C\\fCDVNfAL|@l@rEtCpSD^n@rEx@xFZxBFf@PrADb@@HDd@@FBT@N@\\@d@@f@?RAVA^C`@CT?@Ij@CVIb@Op@EPOj@Mb@W|@K`@Mb@S~@Mn@EXCVAFE`@ARC^AT?@?PAd@?D@b@?L?J@VBj@Dd@Hf@Hj@Pt@Lj@Px@Pv@p@hCl@fBn@vAz@pAn@v@hA|@h@Zr@Zf@JF@v@LN@T?X@^AZAb@G^Gb@MXKPGl@W`Ay@lAoA^_@Z]\\a@h@m@hAsAVYDEvAcBtAaBHI|F{Gz@aAZ_@z@_Ah@o@fBsBZa@d@g@pAsAb@e@b@a@RQ|@w@JKbBoAn@c@nFgDd@WhHcE`CiAbAc@r@WzCaAdAY`@KjCs@b@MdAY`Bc@tKuCt@QbBa@@?l@K|@I\\Av@Ad@?d@Bj@HD@ZDj@J`@Jb@NB@\\LXLn@ZXP~@p@NHdE|CvAv@VJb@NHB|@VxATlAFfB@vAODA`Ca@vFkAdASlCk@vDw@hAWVEtA[`FmAFAbDw@NEnDw@RENEvA_@dQsDtK_CdLeCz@WfC}@|CqAdBy@dEiB`@SjEqBxCqATKn@Sx@Yl@O\\IDA~@ODA`AIdAGjA?`@?b@@`AFJ@b@Bb@D|Gf@fAH|DZX?V@H?fAAb@C@?h@GXC\\GXIf@MZKPEFCXMf@Uf@YHEnCaB|IsFbUgN`GqDrBoApDcClDsB`EiBp@Qv@Qr@OlAMnBOnGWpCKbBGnL_@~FQbDM`AKv@IpAQ^GRCn@O`k@gM|OoD`@KlNaDtFmArHcBtg@qLb@KfBc@lx@kPjDw@hRuDvFiAt@ObAW`A[p@Wn@[l@]j@_@pBmAnDqCdCmBrSeOdAq@~Ay@xAo@j@QZI`@Kb@KZIhASB?b@ERCp@Ed@AT?L?rD@`IDb@?rDBb@?b@?b@@nC@b@?jKD~SJfCOpAOb@I@?ZIFA^Kl@SXK`@Ox@Yj@YJETMVMhBqA`Au@f@e@fCuC@Cr@}@bDaFlAiB`EiGhDkFx@oALQr@iAhBqCt@iA~C_FZe@t@iAXe@t@iAZe@hBsCZe@Xe@xOgVfHyKbLcQfAaBvD}FlG{J`@o@b@{@b@}@fAiCXu@z@wC\\mAf@uB@EViAb@}Bp@_FJmBDw@F{@FqAFuABw@@o@@uAAeCA}C?[k@cv@E}CGwHAqCAk@A}D@kABiABk@D{@LoALgAFc@Hc@H_@Hc@Jc@J]XaA\\_AVq@n@qA\\o@T[HMp@{@v@y@lDaDfCcCjBiB\\]PQjL}KlKaK\\[vCuC^[\\]zAyA\\]xBuBvCsCvDqDtEoEpAoAnGgGjBiB\\[^]j`@o_@|TkTz@y@zAyA\\]tEoE|@y@\\]\\]\\]^]\\[xBwBrPaPfAeAzOoOdAcAnIcI^]xAwA`B_BxLkLpAoAtFmFd@e@bC_CnBoB\\]XYdCwBXUx@o@`@_@BA\\Yd@]XUFCj@a@d@[d@[`@U`@W@?\\Q^Uz@c@HEn@]p@]h@Up@Yl@Wl@Ud@Qd@Qb@Ob@OLETGb@Mb@Kb@K\\Ib@Kh@Kb@If@I`@I\\G`@G`@Gd@Gd@If@EBAd@Ed@Ej@Ef@En@El@Eh@C~@EjAGhAEt@Eh@EjAE@?x@Cj@Ch@CrAEp@CFAr@C|@EhAGZAv@C~AGXAfAG@?dCMj@Cb@Cv@EtCKHAhCInBKvAGtCO`EMhIa@xKe@`[wAb@CdS}@pMk@b@CHA|@EnCKb@CrDQbH[hLg@rDQjBIdAEnCMnCMb@AnCM~H]hAGb@CjBKrDQrf@yBbI_@fAEhAGhBIb@CVAJAjDOzDKpDA~Y@b@?bR@jB?rD?fA@zF?^?bGAv@AN?vE@fA?x@?tA?bI?D?hC@fA?|C?v@?nC@`@?pC?~B?nH?d@?vI@pIAF?fC?n@?~C?fF?~@@jBBpDLb@Bb@BX@zAH`BJvALzAPnAPlARjATtB^b@H~A\\rBf@XHj@NlA\\XJzBr@tCbAzChAvBv@|Al@nAd@THJDrBv@vTjIVH~KbEjRfHvAh@tBt@lC`AhBr@tAf@bA^~@^nAb@hAd@\\LB@lAb@`A^jAb@x@Z`A^v@Xp@Xp@Th@Rj@Rb@Nj@Ph@Lh@Hl@Fj@Df@Bd@?`@?@?n@C`@Ab@GZE\\Gx@Qd@K^M^M\\Od@Sb@UfAo@dAw@@A\\Yd@]dAaA`A{@l@g@VS|@o@|@g@dAi@l@UVKHEt@Wp@Qh@M\\GfB_@p@OxDw@vDy@nCk@fCi@fDo@vBe@~Cq@pHyAzCm@|@QnAW|@Q\\GZC^Ex@G|@Ap@?P?P?l@BhAHpAPpAXbAXdA^dAb@~@d@~@l@z@l@p@l@t@h@pAfAHHt@j@n@h@r@l@z@j@t@^r@^z@XfAV`ANz@Hx@@x@?p@Ex@Kn@Kl@Oj@Qp@Y`By@`C{AjAs@fAq@rCgBbDqBlCgBlAw@nBoArBsAhBiAlBoA`BcApAw@z@c@~B_AzAm@lBo@~@Uv@OnFgAjZoEzGcAvEs@tBe@~Bm@xBu@zB}@|Ay@^QbBeAPKnJ}G`FoDxHqFRO~BcB~DuC`Aq@~BcB^W~BcB`@Y~AiA^YHG|AaAvAo@h@SvAWZCb@EHAlAER@fBBnBD|DHv@AdAKDAb@Kh@M~Ai@BAtA_@NAZEFAf@A|@?hBNt@DV?P@j@Af@Gj@M`A]t@]h@[r@o@LOl@w@d@u@\\q@tA}CN_@|@mB~@aBfAgB~AmB~@}@zBuBzAuAzAwAjBeBvAwAzAwALK\\[z@m@j@[PIPENETCT?V?T@XDVHLB`@PXLTNXX\\b@NTJPTh@L`@Nf@Pn@Jl@Fd@Fj@Bf@DzANnGFjC?BB`@BVBZF\\@HHh@H\\J`@J^?@LZHTJTLTNXX`@FFLNPNPLVPB@JDNHDBTHLBTDJ@D?R@V@TAF?\\ETGJCLERI@ATMVMb@[LKpAcAdDoC`Ay@n@i@|@o@PMHGxBmAjBu@TGh@Ox@UjCm@zA[dAYdBe@~@]v@]j@[n@a@@AHGROl@e@PMZW`@_@\\[zCmC|@y@|@y@\\[LKlC_C\\[|@y@\\]bCyBhAaAJINMXQTQVORMTMBAZO@AVKZOTK\\MXKb@MDCRGLCBAVE^Il@KlCc@b@GxB]dJwAd_@{FfUmD|Z{EdAQz@KlAOrAOtHk@`\\iCrDYdJq@b@EpCSbAIjBMb@C\\Af@Al@@Z@b@@j@Df@Fn@Hn@Jd@J\\HB?ZJB?j@R~CpAJDxCpAf@R`IdDhDtAbA`@vMnFnChAbEdBzJ~DB@xJ`E^NbDrAfBt@f@Tb@RdB~@b@XTNj@b@d@`@hDdD\\\\hL`LpDpDh@f@d@f@dAnATTFHl@t@x@jAzArBZ`@rAhBpHdKbDpEvEtGbDnE\\f@nIfLxF`InClDfArA`@d@j@l@dAjAz@|@\\^XZ~AxABB|DlD|AnAZXz@j@^V`GvE^Xj@b@zDzCTN`H~E~H~F^X`EzCjBtA~FlE|C~B^X~C~BdIbG`BjA|FlElF~D^\\~@t@`At@\\Vn@d@^T`@Xh@`@FDfAl@"
                     },
                     "start_location" : {
                        "lat" : 50.62070430000001,
                        "lng" : -116.0709173
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "31.6 km",
                        "value" : 31637
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1153
                     },
                     "end_location" : {
                        "lat" : 49.5740788,
                        "lng" : -115.6836428
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBC-93 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-95 S\u003c/b\u003e (signs for \u003cb\u003eWasa\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCranbrook\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eFernie\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "er_oH`braUXu@HU@AVm@Vg@p@oAVe@FMzAsCl@gAl@oAv@{AjGcMjD{G`BcDVg@p@qAlD_HpEiHfEoFVY~@aA^]\\]JMd@a@|@w@DEb@]^Y^Yn@e@NIh@_@rBqAn@]t@_@b@UlBy@zDaBdEeBt@YxAk@xFcCtHaDdDuAhAe@~EwBPI`@QnF{B|Bu@|H_DdC}@rF}BzKuEtSaJjP{GvZgMxAi@nIeDlD{AbDsAxEoBrCkAvMoFnD}ApD}A|B{@nBw@`CaAf@UdFsBfAc@lFyBbGeCn@WbAa@r@[tAk@LGxB}@`@OvB}@rAk@j@UXKtB{@rCkA`Bs@bBq@pAi@`Aa@|D_BfKiEpH{Cd\\}M`@QtImDdQgHpH}CbAa@fBu@bAa@dBs@r@[p@Yz@a@bAg@`@Uh@[d@YVQ^Wp@g@h@_@d@]JIp@i@`@Yl@e@nA_AtAeAhA{@rAcAhK}H|KoI@C|@o@jA}@pAcAlBwApAaA^YhA{@jEeDrB}Ar@i@`CiB\\U^Y|@s@~EuD|GgFhJcHtDsCx@o@BA~@s@dAw@~AmAv@m@bAw@zDwC^YlDkCbAw@j@c@~C_C@AjBwApCuBvC}B|@m@fDgC\\Y~HaG|DyC~AmA~JsH\\Y`CeBjBsArAcA^YdBqA|CaChDgCfDeCjB}AnDqCl@c@^Y~DyC^Y~DyCnG{ElHsF|LgJ|BgB^Y~JsH^Y|BgB^YnA_AnByA^Y|DyCnEeD|FmE^YnDmCfCmB^Y~C_C~EuD~BgB~@s@^Wz@q@`BoA~HaG|EsDBCzC{BpEiD~AmA^Y~@q@^Y~@s@|C_C~@s@~BgBrAcAJGzBeBBA|C_C~AmAfEaDtAeA~AkAPMlA_A~AkA^Yf@a@VQ^Y~@s@^Y|@q@~BiBJId@_@^[bA{@v@q@\\[t@q@d@e@\\]\\[|@}@HIRSx@}@z@_A\\_@HI^c@l@o@NQLMlFaGbH{H\\_@tB_C\\_@Z_@`BgB~BmCzBcCtB_CZ_@hG}G\\_@vA_BZ_@xA_BZ_@\\_@tB_C\\_@Z_@z@_A\\_@Z]pD_En[}]\\]vA_B\\_@pC_DtEiFpBwBtA}AtA}AtHmIx@_Az@_AnFcGn@q@d@e@^_@XUj@e@l@g@d@]VQz@k@p@a@|@e@j@[`@QTKx@[`@Ov@Wr@Up@Q`AUhAQ\\GhAMj@Gn@EB?b@C^AbAC|@?@?^?^@X@|@Dl@D`@Dr@F`@F`Cb@\\FZHFBTFVF|@Xx@\\LDr@\\dBv@lBjAb@VRNbBnAxAlATTPN~@~@n@n@v@bADDZ`@p@`ARX|@rA\\j@h@~@NV\\n@^p@lAlCjArCR`@P`@l@tATj@bA~Bh@lAl@tAfC`GHNLXTh@l@tAVh@Tj@LTxC`HvDzIXl@pBtEBHN\\d@jAZ|@h@zARl@BFNd@DNRp@j@lBXfAV~@J^Lj@XlAVlAVrAZzALr@vAnHx@hELr@Np@vAnHLr@H`@BN\\dBLp@Lr@Lp@\\dBLp@Lr@j@vCLr@Lp@x@jELp@ZdBj@vCbArFzA~Hx@rEzAdIbAjFhA~F?DfAvFpAbHtAnHNr@d@hCBLNp@Lr@F\\z@zDVbA\\vAh@hBTt@Rl@X~@`@lAFPJZTj@Nb@DF`@fAf@nAb@`AJTVj@JPVh@HRv@zA^p@Vd@?@Xf@V`@n@fADFTZXb@jAbBhAxA|@fAh@n@t@x@|@z@LLNLb@`@j@j@@@v@p@DDj@d@PNVPn@h@VNj@`@RNPLh@XDBf@Zj@Z@@f@VXLb@Rp@Xz@\\pAf@t@VTHNDPDf@Np@PB@rAVz@N`AND@`AJnAJnBL`@@lABPAd@@xAANAZAd@C|@Eh@CB?PCPADAt@GNC^EBAf@GFALCb@IFA`@I@?LCHCd@Kj@MHCVITGTGBAFCp@S`@OZMp@Wv@]v@]LGl@[`@SVM\\QJG^Sp@_@nAu@l@a@d@[^WLKFEDCXSb@Y|@o@~DsC~DuC`@W^WNKNKFCLGHCVGJCRAH?F?@?F@HBH@FBJBTJBHDFFFFHDHHNHXFXB^?\\?RALCLCLCRCHEHABABEFKLGFCBMFGBGBI@G@E?GAC?C?GAGCCAGCAAECOMGIOSKOCEEEECOG"
                     },
                     "start_location" : {
                        "lat" : 49.81043220000001,
                        "lng" : -115.76881
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "86.3 km",
                        "value" : 86299
                     },
                     "duration" : {
                        "text" : "56 mins",
                        "value" : 3335
                     },
                     "end_location" : {
                        "lat" : 49.505511,
                        "lng" : -115.0674003
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eBC-3 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBC-93 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow BC-3 E\u003c/div\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "_mqmHvmaaUQg@Qk@Mc@Qm@COEOKk@Km@Io@Ig@Ee@Ec@AWC[Aa@Ce@?EAu@?AA}@?}@@i@?EFgBFu@Di@Hs@Fc@B[Lo@BQBKJg@@CF]J_@FSJ_@HYNe@Ri@Rg@P_@`@aAf@iAfFeLdA}BzAiD~@qBVk@f@aAZo@r@sA@AR]Tc@PW|@uA`AyAlAiBPYnCaEj@}@jDgFf@u@pIiMfA_B`BcCjBqCrFiIV_@`CkD`ByBpAaBt@}@bBoBr@y@x@}@~AaB`A_A\\]JK`A}@|@w@hC}B|@w@vHuG\\[`Ay@xBkB\\[^Yr@o@rGuFj@i@|A{AfBiBDE`BgBzA_BjAqA@AdDuDp@y@|AkBZ_@dFiG|D{E\\a@jDeErBeCZ_@dFiG`EaF\\_@d@k@hByBZa@rBcCdFiGlDeEZa@lDeEdFiGtAcBnEmFvGaIlEkFbFcG^e@f@o@bAoAV]d@o@T]j@y@x@mAjAkBv@sAf@y@p@mATa@P]j@cAd@}@DGP_@DIj@mAVk@N]BETk@JUtEyKfCaGPc@|AsDd@iAr@cBxCgHfAgCdCcGTi@|CoHTi@bHsPl@uAnBwETk@tD}IN_@hCeGzAmDfA_Cp@wABGhAaCv@_B`@w@v@{A`AmBVg@LUJQdAoBfGiK`G_KfByC~B_ELQrBoD`C_EtDkGxBuD~KkRnEsHJQd@{@hAqB@C|AwCx@aB`@w@Te@j@oADKbA{BBCRe@Ti@jHiPTk@rBsETk@bJqSpEgK~DaJj@qAz@iB`AqBr@uAjAyBl@eAj@cAd@u@z@qAxAyBrBwCzAwBzUu\\bE}FpC{DzCiElAeBxB}CbA_Br@kAp@kA^o@v@wApA_CfBqDN[LWl@qAd@eAh@mADI`@aAx@sBv@sBpAsDh@_Bh@_BZeAbAiDXaA~@kDVcANq@Po@^aB@?Nq@rAqF?ANo@@??ArAqFNq@`@aBNo@@A^_B`@aBVcALi@Po@Nq@`@_BPq@vBsItFoUp@sC`@cBVoAZaBd@aC`@{B^uBTuAXgBTgBLaAVmB`@gDJeALiAJmA?AJeADs@Bs@Bs@@_A@w@?i@Cy@GcB?IMcCUqFA}@AoA@qA@k@?GBw@B}@Do@B_@BUH}@f@mEJq@b@{C@IRuATkAPw@Ne@Rq@L]`@kAjAmCTg@?Al@qAj@yAL[FQRg@@CZeAf@}Ad@aBDS\\sAR{@R}@Lu@Lk@PkADUJs@BSL{@TqBN{AL}ALaB?AFu@@OJqBZmGRiEXkGv@oQVkFBgA@a@?_@@eA?sAA{@Cu@As@A_@GiBIqAEy@M}AOkB?CKgB?ACu@Ac@AQ?A?c@AY?oA?_AB_A?CDw@Bs@PyCDaABk@JiCJuCBiB@_B@{CAeBAy@Aw@EeA?UAWA_@?OAm@A]?c@Ae@?I@a@?I?m@@I?Y@W@c@BW@WHgA@KFs@?AHs@BOJ{@F]@EF]BMLs@@CLm@@EJc@@ENg@Lc@FQJYb@iAP_@^y@f@aAHOLWjAuBXg@Ve@DG~AuCbAkBhAsBvCkFVg@HK|AmCP[FIpAyBlB_DlCqEtGwKXe@|PgYbFkIv@oAbFoIdBuC~GaLzCcFr@kAr@mAZe@r@kAlAqBlGgKT_@hAgBpAgB@Cz@cAX]LMNQ\\]?A\\[d@c@XW\\Y\\YDCVSl@c@fAs@~AeAhAq@vBuAp@a@xEyC`C{Af@YzEyCFEjAw@HGpB_Br@o@b@c@~@cAf@q@DEZc@Xa@d@s@t@qA`@y@^w@Rg@P]Tm@Na@Pi@Vq@l@iBp@qBp@sBrBuGPo@X{@tCmIbBgFRm@x@iCn@qB`@oALc@v@kCd@}Ad@}AX_A^kARo@Rm@`@sAj@iBPi@|@iCf@}AVw@x@{BRm@Tk@HUHWLYHQN[FM\\w@P[Vi@DKVg@Vg@dCsEvBuDXe@Vg@v@sAfAoBXe@jAuBVg@h@_AzLeT`@q@jAuBVg@Va@p@mAr@mAp@mAv@qArAaCfB{CBGtJeQdB}CjAuBp@mAr@mAp@mAb@{@Xg@zNmWXe@dB}CjAsBhEwH@A^o@Ta@r@cAdR{VZc@T[`AsARY@CXc@`@m@fAiBXe@LQXg@Zm@^u@Vg@|Q{^dNoX`BcDFMNYL[N]LYNg@ZaAnAuDzAmFRo@zAkFlB{G@?lBgGhDgLd@}Av@iCPw@Nk@@ENu@TcAPy@N_A\\mBTaB?AHi@@GFg@@MLiA`@_EFu@l@iGd@uENuAJiAFu@Hu@Fu@b@uEd@sELoAPyBLcBF}@DaAD}@DcBBsADuB?oA?a@?kA?sG?o@BkIHiC@Y@]B]Ba@Bc@@CB_@BUFe@J{@PkAFc@BSPcAb@qBTgATaANm@V{@@CPi@HU\\gA|@eCzBoGdBaFbG{PxAgEnAwDdBgF\\eAV{@XiAf@oBR_ANq@^gB|@aEh@cCz@aETiAfA_EPo@No@DK`@oALc@\\u@DKN]d@cAHMVi@Vg@R_@DGhAmBnCqDrAgBzAsBpBgCZ_@bEiF^e@`@i@n@_ArAiBjBoClBmClBmCzBaDjA}AjA_Bt@gAZg@j@aAb@aAl@aB@?d@qATw@To@j@wBFWf@{CNaA\\kDHqCBe@BeA@yBA_BCuAEcBGw@Go@MkAGg@S}Ag@gCQ}@aAaF_AoF{@wEKk@S{Ae@yDe@aF[sD[cESaDW{DWiDi@cIEu@oAaRSwCKcBIuBCaCAmABmA@e@HsBDq@@EJiAFi@NeAJ}@@Gl@mDd@_BDI\\gARg@n@uAl@oANWNWxAuBpAqBz@kAV[BEJObEsFbAsA|@mAzDqF`CcD|@yAnB_Dh@eATe@h@oA\\w@Ri@j@gBx@_DfA}E@ELq@|@eE\\eBNy@\\gBNiANgAJw@Fm@Dq@HqA@c@@W@i@@cA@_@?W@o@?q@A{@CoAAo@Ac@E}@C_@EaAIgA{@wL]gF[yEEu@Ek@?IAWCc@CkAA[?C?a@?iDBmABgBBaBCmA?AEaAIgAEWGm@SeAKe@I[]eAc@wAi@oBs@oCY{AQwASuCGaAG_AeAcRI_BWeEGgBI{BAq@Cg@?g@A_A?mA@kA@}@@i@@UBs@DeADgAHoAD_@@QFk@NmANmALy@L{@@GLu@Ha@DWNo@Je@Lg@BOJYH_@l@wBb@qA\\_Aj@sAXi@b@{@Vc@P]v@mA^i@hA}Az@iAZc@Za@z@cAHKjAyAHIzE_GHKZa@JMNQtAeBZa@PUJKZa@PSd@m@fB{B~AoBPUHKdC{C|AqB\\a@PSv@cAbAoAjAwApBgCHKPSHKjAyA`AoAfC}CZa@bFkGZa@zBoCzEcGrAcBhMyOZa@|GoI^e@pCoDzBmCvAcBv@}@h@m@l@m@p@q@l@k@f@c@x@q@`CqBdE{C~BcBdCgBzHqF@A^U~CyBdGmEjI_G`OmKhI_Gbf@e]^Y`H}EvFaEzAeAvAcA`H_F^W~AiA`CcB~C{B^Y^Wp@e@LK~C}Bb@[`D_C|@o@~BcBdAu@tDkC^Wb[uTTOjDcC`LaI~BaB`MyI^YlA{@rNcK~JkH^W^Y`CaB^Y~AiAFGfCiB|@q@vAmA~@{@f@g@fAiAdBuBn@w@j@u@vAqBpCiEHObC{DbC{DvBiDDGXe@|@uAj@_ARYx@qA^m@v@kA`A}Az@uAt@oALSHMJSLUHQJUf@iAZ{@HSHWJ[HYJc@T}@TgAH]F_@Hg@Fi@Js@Fo@Fo@F_ADu@Bq@?ODeBBcF?uC?o@?EAeD?g@?O@u@?w@?u@?w@@mB?w@?u@?s@@y@?w@?_C@kA?o@?g@Aa@Ac@Cg@Cc@Em@Io@E_@I]?CKe@U}@Qe@M]M[MYUc@GKWg@o@oAg@_Aa@y@GK]y@GMOa@Qa@ISGQ_@mAQk@[oAS_AAIEQKq@Km@Ga@]kC]cD_@}FAMWeDMyBMeBO{B_AaOg@yHy@_MGq@Eu@Gu@E_@CSGe@CMEWAEGSI]Qm@CGEIKYACGMEGIOU]MOAAMOCAKMMICCKGAASMMEIEICECOCOEIAGAMAA?KAK?I?MAQ@C?M@C?YB_@FUDk@LE@m@Nu@PGBYHSFc@NSFMDiAZ]Jq@N[FSDQ@w@Bc@EK?WEYC[I_@Me@WUOWQOKMO[]QUQSOW]g@AAWi@W{@Ma@EOI_@AEI_@CKGY?EIi@G]AMGi@AQC_@I_AGk@MiAC_@KcAWeCIy@Go@CQQwAMaAGg@SuA]_BSq@I[K_@c@uAQg@w@}Aw@yAWg@s@mAWg@o@eACEYg@KQKUm@gA]q@[u@Wu@Uu@Os@QgAMeAKuACu@Ca@CmAIkEG}CQoF?QImCGiACg@C[I{@K{@My@O}@UiAsAeGO}@QiAQsAOwAGs@Eo@Ca@Eg@s@qHWaDW_DQ{AMaAIi@M_AIi@M{@UsAg@{Cg@qC{@wE_@wB[kBc@sB]_BQq@AIOe@Mc@Wk@CIUi@AC}@eBgA{Bc@y@EKYm@[s@Wy@Mc@I[Ie@Mm@Ie@Ie@Kw@Gs@Es@Cy@?]AYGuE?m@GsKMwFIeCCw@C{@IeCCiA?w@?]@]Bg@@M@YFk@Hq@Fe@Je@Jg@No@ZgAhBmGb@aBl@sB^sAZmAJe@Hc@DUB_@B_@@[@M?[?YAS?UAQCSC]G_@EQEOi@cCOq@Ic@Ow@AIEWEU?ECMAUAQ?SAg@?y@@g@?EBw@@[DmABo@@IBi@?K?U?_@?_@Ac@Eq@Cg@AGC[EWAAG_@EOAEKa@CGg@_BoAyDOi@AGOo@Kg@My@K}@Ge@?CGs@GgAKkBCg@Eu@UyEEu@Eu@OcDIeBKeB?MCa@CSCc@K_AAGIk@Mw@?AMs@?AOo@G]Om@Su@GMSm@IUKUc@mA[u@Wi@Uk@Uk@Se@IUK[Ma@Mc@m@gCy@yD_@iBi@cCCIMi@Uw@?AGQUs@[u@CG_@s@Wi@k@{@[c@]c@KM]_@OOa@a@kAkAcA_AqAiAq@i@c@]w@o@WSEGu@u@c@c@]]]a@?AQSOUQYOUMOKQa@w@CEWi@GMQa@Qc@KUIWgBaFSk@y@}Bm@cBM_@EMYw@Qe@Sg@g@kAS]IQCCMSIKEGSW[Ya@c@QOi@k@a@a@y@u@i@g@QSo@s@g@k@CCi@o@KMeAsAOQ_@e@Yc@_@i@a@k@e@y@gF{I{AyBq@_A[]a@c@k@g@y@o@o@g@]WOM}@m@iAw@c@YEA[QEAg@Wa@Oa@Ok@OcAWcAQ{@MgBUuM{A_AKMCSEMA[IUGYKYM_@Q]Q_@SaAm@w@o@{@s@aDaDCC{BuBWUYSUQWMWK[Ma@Kc@I]E_@A_@AuEPwBFW@_A@[AYASC[EKCQCQEEAYI[Kc@OGEUMIEYMw@m@OIQMMMi@e@SQWWEEY[a@a@MOOMy@_A]]{@_AQSSOOKQIQGMEUC]Ac@A[?SBM@QBK@E@IBSHC@MFUNOLOJ[V{@~@c@d@WR]TSJ[NWFC@[Dc@DC@iBD_FJWAUAYESEYGUISKOIGCGC}@g@]UWOUMUIWKSEKCKCMAM?K?K?O?O@OBQBOBGBIBQFMFKDGBEB?@KDQLo@d@a@\\]ZYVOLEDGFSLQJKFKFSJYJ]JWFUDiBZC?GB[DG@c@HiBVeC^}@NoCd@I@iBZgBRm@Fu@Ha@B[Be@B_@@iCB{A@eAA_BC_BAW?]@]@YBQ@QB[F[FWFi@Na@NSJ[L_@T_@R[TSPC@KJg@d@GHYV]`@Y^iAzAa@j@_@d@SVQR[ZSPQNSNUNMFKFWL[Lc@LA?WD]Fi@DO@Q@M?E?S?o@AeCQEAc@EcD]}C]eBQcAKa@EUCMASC[CWAG?a@CU?O?m@AQ@Q?[BSB_@De@Je@Je@LWH[LYL]NWN_@TA@s@n@kAdAyEpEo@j@YXCB{@r@aBjAy@j@_Aj@sBdAgAh@e@Re@P{Ah@u@Rs@NYFeB`@c@HSDi@Hk@HiBPA?uBPWBoCVmCVkBPeJz@sBPcIv@_Hn@c@DaIv@c@DuEb@qAVWFy@PqBf@o@Rm@RgBr@s@Zi@Vm@XGD_@RGBYPQJo@`@sA~@uAdAw@l@[XURkAhA}AbBmAvAu@~@ONw@fA_AvAqApBGJQXmHtLyA`C[d@mAnBq@hAsAzBmB~CsCtE_AzAk@z@o@|@c@j@Y\\YZ_@`@_@\\[ZA@[XCB_@Zo@d@s@f@k@\\g@Xg@TcAd@c@P]Lw@Tm@Pe@JwATUBmBVaBRcFj@k@HQB[F}@RYHYHa@N_@P_@P]TSL_@Z[V]ZYX[^a@h@a@j@a@p@A@Q\\QXMXKRKRKV_@~@A@mAdDy@|B]x@[v@]t@i@`Ae@z@U\\KPg@p@_@d@e@d@gBdBaHrGqDdDcA|@YT_@XSNeAt@kAv@{HzEqC~Au@`@e@R]Ni@RA@_@JI@_@F]DG@o@FO@}ALkBRK@c@DE@[FM@UFQDy@X[Lc@PwCnAq@ZwAn@kBx@mBx@a@Pg@RaFzBiBx@a@PyAn@sCnAa@PIDeGhCgChAa@Rw@\\oAh@gChAa@PC@aBr@a@PkBx@gCfAoD|AUJcAb@KDq@XaAd@w@f@[TSNMHsApAs@z@cBpBkFvGc@h@[b@[`@[`@_BnBy@z@_A`Ae@`@g@f@k@b@_@ZwBxA[TiCdBw@h@QLMJmAv@wA~@cBdAwCpBIFi@Zg@VMFSHe@Py@RsIfBc@B]FWFUF_@LeCt@mA^iCx@oGpBwBv@_@XmCv@sDbAcCr@a@LaEjAuA`@eCt@wBj@q@Nq@H_@Dk@@[?E?]Ai@Ea@Gc@Gg@Ms@Wc@S[OcAk@gBqAoFyDkCgBm@_@k@[e@Ss@So@Oe@IYEG?q@Ga@?W?s@Fy@N]Hi@Ni@To@Vy@b@yAv@qAp@u@`@yBlAkGfDuAt@{N|HqFvCwBjA]P{@d@_Af@o@\\gCpAgFnCwC|Aw@`@w@ZWJe@Ng@L_@H_@JSBOBm@Ja@D[Bk@Fk@@k@Bm@?i@ASAI?[AeAGE?]AKAaAGeAGaESiDSc@Ci@Gs@K_@IA?UEMEKCOEMGi@Y_@U[Ua@]a@_@UUQQSUQUSYQYIOKQKUOWMWk@iAkAkCu@_Be@aAWm@}CuGWm@AAUk@q@yAkAiCWm@s@}AWi@eA_CeA}BO_@k@iAcA{BcAyBc@}@gAeCWi@g@gAeAaC"
                     },
                     "start_location" : {
                        "lat" : 49.5740788,
                        "lng" : -115.6836428
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 387
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 49.503592,
                        "lng" : -115.0629223
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e5 St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m`dmHfbi}TNe@Ro@L_@Rm@Rm@Rm@Rm@Rm@Rm@Rm@Rk@Pm@Ro@r@{Bz@iCVw@"
                     },
                     "start_location" : {
                        "lat" : 49.505511,
                        "lng" : -115.0674003
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "48 m",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 49.5040082,
                        "lng" : -115.0628236
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mtcmHffh}TEECCECCAA?C?CAI?K@O?IAEA"
                     },
                     "start_location" : {
                        "lat" : 49.503592,
                        "lng" : -115.0629223
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "qq{rHzjp}R{@dbCpbA~]lfDsC|cAhcCAtvK?bcnAA~`NnAlal@wF~_HqhD~~Hes@xeh@ihG~vScq@nzEzqA~hOxk@hgZ`BzdZ_Jx`f@lD`c`@vp@hbFon@r|J}kB`eOqAbbGtiAx~Aj{CdbFbaDraHfc@jwJbFrhKqvAdgIiBvcOxqBt_KjjBvjJ?|xR~pB|xRbqBb{QxtDvwQd~D~fPhm@`jJw_@~yFrqB~oMlpCxsJfbHny[b_HxxQ`lBb|TlmAzaHd{CjyFjsCnvMtt@v}Px^b`j@`kBffIthBpnS~aD`vQ|y@hrZjqA|{QgA|qXrcArnc@x_A~yJoApiPtDzzXtdCxlRrBzxOgnBzha@_{BdqLeGpuRd{@hwSywE|xIywD~gIqcEjgFovD|`KogM|ma@}tI|nd@ggn@`jqAgzLnbe@wuNtc\\}}M``q@{aG|vTiLxgGuxDtrHufAhk@el@bbC_{@n}Bc_DtZ_cBnkDObjK?`dO{@`zb@qrC`gF_c@|dI~S~cT~dAdrFsa@v_OsoDluHgz@rfHa@dzYavAhkTgKlxv@pd@dlg@o[pcA_uEpM{sBvjIwkEzZaaBy{BamB}_BmrAjj@{s@x}CeF|qCxMzrBkDgU`C~xCh^rdGovBfpDozA~fCuh@lsBmf@|`d@gKno[__ApdLyhChrK}pFhuRp{Ffrf@hzFtlNpcAzeCbAjbFx{AhyDdXvzGjE`vDry@tgCaMnrG}sDbwG{nEpnEayE|zHcoKd~S_Ld}BzzA|hEfwAxnKh}Al~EUd~GeqGjsJisHfzUwr@lqHrZhpEjsArcIbjClmD~hF|mKtiBpeD`iB|h@r{Ay|A|tAa_DdaBclDn}IsrKj`EonGlgEauCjjDbAjvAl`CrfEzyHv^vv@`bAkLlhBpiBfpBgcChvE{oAfdEaxBfnH{uLnvDcxBpeHceBlZfvJnzCxiDdV`~Flk@p`Flg@jiApgByIpbLqeIvaH_oCz_Dme@d`F}|GxtGqiHliIykEtrBbqAbq@vlCz\\po@~gCc}@bfRawEtbEqoCduAkpFvlFq}ElwCmR`fJeQthEjgAr|I{qBtuB}gAn]vm@vyAu}@peHdKz~E`yE`uFwsDz|NkpIlfK_hJvyAld@piAveEpcCzcCjd@q_AtsIiaMb~GqgOn`@obHtvEwaIrmF}aMzgBghKzv@}|DeQshDlwKsmK|hBeqCaUkrBudA}wBieBgiMc~Cy|Bo|BvLwtEzgAaiEdtD_rCxdByjCfR_zB|^{]adB"
         },
         "summary" : "Trans-Canada Hwy and Trans-Canada Hwy/AB-1 W",
         "warnings" : [],
         "waypoint_order" : [ 0, 1 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
