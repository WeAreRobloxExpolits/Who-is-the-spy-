--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v82=0;while true do if (v82==0) then v19=v0(v3(v30,1,1));return "";end end else local v83=v2(v0(v30,16));if v19 then local v93=v5(v83,v19);v19=nil;return v93;else return v83;end end end);local function v20(v31,v32,v33) if v33 then local v84=(v31/((5 -3)^(v32-((879 -(282 + 595)) -1))))%((3 -(1638 -(1523 + 114)))^(((v33-(2 -1)) -(v32-(620 -(499 + 56 + 64)))) + (932 -(857 + (105 -31))))) ;return v84-(v84%1) ;else local v85=(570 -(367 + 201))^(v32-(928 -(214 + 713))) ;return (((v31%(v85 + v85))>=v85) and (1 + 0)) or (0 + (1065 -(68 + 997))) ;end end local function v21() local v34=1270 -(226 + 1044) ;local v35;while true do if (v34==((0 + 0) -0)) then v35=v1(v16,v18,v18);v18=v18 + 1 + 0 ;v34=1;end if (v34==(118 -(32 + 85))) then return v35;end end end local function v22() local v36,v37=v1(v16,v18,v18 + (959 -(892 + 65)) );v18=v18 + (4 -2) ;return (v37 * (472 -216)) + v36 ;end local function v23() local v38=0 -0 ;local v39;local v40;local v41;local v42;while true do if (v38==1) then return (v42 * 16777216) + (v41 * (65886 -(87 + 263))) + (v40 * (436 -(67 + 113))) + v39 ;end if (v38==(0 + (0 -0))) then v39,v40,v41,v42=v1(v16,v18,v18 + (7 -4) );v18=v18 + 4 ;v38=1 + 0 ;end end end local function v24() local v43=952 -(802 + 150) ;local v44;local v45;local v46;local v47;local v48;local v49;while true do if (v43==(0 -0)) then v44=v23();v45=v23();v43=1;end if (v43==(5 -2)) then if (v48==(0 + (1913 -(1789 + 124)))) then if (v47==(0 + 0)) then return v49 * (997 -(915 + (848 -(745 + 21)))) ;else local v109=0 -0 ;while true do if (v109==(0 + 0)) then v48=1 -0 ;v46=(409 + 778) -(1069 + 118) ;break;end end end elseif (v48==(4643 -2596)) then return ((v47==(0 -0)) and (v49 * ((1 + 0)/(0 -0)))) or (v49 * NaN) ;end return v8(v49,v48-(178 + 845) ) * (v46 + (v47/((3 -1)^(127 -75)))) ;end if (v43==(1 + (2 -1))) then v48=v20(v45,21,31);v49=((v20(v45,(125 -93) + 0 )==(886 -(261 + 624))) and  -(792 -(368 + 4 + 419))) or (1 -0) ;v43=1083 -(801 + 219 + 60) ;end if (v43==(3 -2)) then v46=19 -(10 + 8) ;v47=(v20(v45,3 -2 ,462 -(416 + (1081 -(87 + 968))) ) * ((6 -4)^(14 + 18))) + v44 ;v43=3 -1 ;end end end local function v25(v50) local v51=0 -(0 -0) ;local v52;local v53;while true do if (v51==(1 + 0)) then v52=v3(v16,v18,(v18 + v50) -1 );v18=v18 + v50 ;v51=4 -2 ;end if (v51==(1413 -(447 + 966))) then v52=nil;if  not v50 then local v108=0;while true do if (v108==0) then v50=v23();if (v50==(0 -0)) then return "";end break;end end end v51=1818 -(1703 + 114) ;end if (v51==(704 -(376 + 325))) then return v6(v53);end if (v51==(2 -0)) then v53={};for v94=2 -(15 -(9 + 5)) , #v52 do v53[v94]=v2(v1(v3(v52,v94,v94)));end v51=(377 -(85 + 291)) + 2 ;end end end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v54=(function() return 0;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();local v59=(function() return;end)();local v60=(function() return;end)();local v61=(function() return;end)();while true do if (v54~=(3 -2)) then else local v89=(function() return 0 -0 ;end)();local v90=(function() return;end)();while true do if (v89==(0 -0)) then v90=(function() return 1824 -(1195 + 629) ;end)();while true do if (v90==(1 -0)) then v60=(function() return v23();end)();v54=(function() return 243 -(187 + 54) ;end)();break;end if (v90==(780 -(162 + 618))) then v58=(function() return {};end)();v59=(function() return {v56,v57,nil,v58};end)();v90=(function() return 1;end)();end end break;end end end if (v54==(2 + 0)) then v61=(function() return {};end)();for v96= #"|",v60 do local v97=(function() return 0;end)();local v98=(function() return;end)();local v99=(function() return;end)();while true do if (v97~=1) then else if (v98== #".") then v99=(function() return v21()~=(0 -0) ;end)();elseif (v98==(2 -0)) then v99=(function() return v24();end)();elseif (v98~= #"91(") then else v99=(function() return v25();end)();end v61[v96]=(function() return v99;end)();break;end if (0==v97) then v98=(function() return v21();end)();v99=(function() return nil;end)();v97=(function() return 1 + 0 ;end)();end end end v59[ #"xnx"]=(function() return v21();end)();v54=(function() return 1639 -(1373 + 263) ;end)();end if (v54==0) then local v92=(function() return 0;end)();while true do if (v92~=(1001 -(451 + 549))) then else v57=(function() return {};end)();v54=(function() return 1;end)();break;end if (v92~=0) then else v55=(function() return function(v111,v112,v113) local v114=(function() return 0;end)();local v115=(function() return;end)();while true do if (v114==0) then v115=(function() return 0 + 0 ;end)();while true do if (v115==0) then local v172=(function() return 0 -0 ;end)();while true do if (v172~=(0 -0)) then else v111[v112-#"/" ]=(function() return v113();end)();return v111,v112,v113;end end end end break;end end end;end)();v56=(function() return {};end)();v92=(function() return 1385 -(746 + 638) ;end)();end end end if (v54==(2 + 1)) then for v100= #".",v23() do local v101=(function() return 0;end)();local v102=(function() return;end)();while true do if (v101==0) then v102=(function() return v21();end)();if (v20(v102, #".", #">")==0) then local v116=(function() return 0;end)();local v117=(function() return;end)();local v118=(function() return;end)();local v119=(function() return;end)();while true do if (v116==2) then if (v20(v118, #",", #"\\")~= #"}") then else v119[2]=(function() return v61[v119[2]];end)();end if (v20(v118,2,2)~= #"]") then else v119[ #"91("]=(function() return v61[v119[ #"nil"]];end)();end v116=(function() return 4 -1 ;end)();end if (v116==3) then if (v20(v118, #"asd", #"19(")~= #"|") then else v119[ #".com"]=(function() return v61[v119[ #"xnxx"]];end)();end v56[v100]=(function() return v119;end)();break;end if (v116==1) then local v121=(function() return 341 -(218 + 123) ;end)();while true do if (v121~=(1582 -(1535 + 46))) then else v116=(function() return 2 + 0 ;end)();break;end if (v121~=0) then else local v197=(function() return 0 + 0 ;end)();while true do if (v197~=1) then else v121=(function() return 561 -(306 + 254) ;end)();break;end if (0==v197) then v119=(function() return {v22(),v22(),nil,nil};end)();if (v117==(0 + 0)) then local v220=(function() return 0 -0 ;end)();local v221=(function() return;end)();while true do if (v220==(1467 -(899 + 568))) then v221=(function() return 0 + 0 ;end)();while true do if (0==v221) then v119[ #"91("]=(function() return v22();end)();v119[ #"http"]=(function() return v22();end)();break;end end break;end end elseif (v117== #"|") then v119[ #"-19"]=(function() return v23();end)();elseif (v117==(4 -2)) then v119[ #"91("]=(function() return v23() -(2^(619 -(268 + 335))) ;end)();elseif (v117~= #"91(") then else local v226=(function() return 290 -(60 + 230) ;end)();local v227=(function() return;end)();while true do if (v226==0) then v227=(function() return 572 -(426 + 146) ;end)();while true do if (v227~=0) then else v119[ #"19("]=(function() return v23() -(2^(2 + 14)) ;end)();v119[ #"0313"]=(function() return v22();end)();break;end end break;end end end v197=(function() return 1457 -(282 + 1174) ;end)();end end end end end if (v116==(811 -(569 + 242))) then v117=(function() return v20(v102,5 -3 , #"-19");end)();v118=(function() return v20(v102, #"?id=",1 + 5 );end)();v116=(function() return 1025 -(706 + 318) ;end)();end end end break;end end end for v103= #"/",v23() do v57,v103,v28=(function() return v55(v57,v103,v28);end)();end return v59;end end end local function v29(v62,v63,v64) local v65=v62[(3127 -(157 + 1718)) -(721 + 431 + 99) ];local v66=v62[1273 -(945 + 326) ];local v67=v62[7 -(218 -(22 + 192)) ];return function(...) local v68=v65;local v69=v66;local v70=v67;local v71=v27;local v72=1;local v73= -((3 -2) + 0);local v74={};local v75={...};local v76=v12("#",...) -(1 + 0) ;local v77={};local v78={};for v86=1500 -(1408 + 92) ,v76 do if ((v86>=v70) or (3377==3656)) then v74[v86-v70 ]=v75[v86 + (1087 -(461 + 625)) ];else v78[v86]=v75[v86 + ((4406 -3117) -(993 + (1313 -(697 + 321)))) ];end end local v79=(v76-v70) + (1464 -(1404 + 59)) + 0 ;local v80;local v81;while true do v80=v68[v72];v81=v80[1172 -(418 + 753) ];if (v81<=((21 -13) + 11)) then if (v81<=(1 + 8)) then if (v81<=(2 + 2)) then if (v81<=(1 + 0)) then if (v81==((710 -181) -(406 + 123))) then v78[v80[1771 -(1749 + 20) ]]={};else local v123=0 + 0 ;local v124;while true do if (0==v123) then v124=v80[1324 -(1249 + 73) ];v78[v124](v13(v78,v124 + (2 -1) + 0 ,v80[(1913 -(468 + 297)) -(466 + 679) ]));break;end end end elseif (v81<=(4 -2)) then v78[v80[5 -(565 -(334 + 228)) ]][v80[1903 -(106 + 1794) ]]=v80[(3 -1) + 2 ];elseif ((v81==(1 + 2)) or (2336<1393)) then if ((v78[v80[5 -3 ]]==v80[10 -6 ]) or (3904>=4458)) then v72=v72 + (115 -(4 + 110)) ;else v72=v80[587 -(57 + (1777 -1250)) ];end elseif ((436>=123) and (v80[(3311 -1882) -((94 -53) + 1386) ]==v78[v80[107 -(17 + 86) ]])) then v72=v72 + 1 + 0 ;else v72=v80[(10 -4) -(2 + 1) ];end elseif (v81<=(17 -11)) then if (v81>(171 -(122 + 44))) then v78[v80[2]]=v64[v80[5 -2 ]];else local v129=0;local v130;local v131;while true do if ((500<1816) and (v129==(0 -(0 + 0)))) then v130=v80[(3 -1) + 0 ];v131=v78[v80[1 + 2 ]];v129=1 -0 ;end if (v129==(66 -(30 + (93 -58)))) then v78[v130 + 1 + 0 ]=v131;v78[v130]=v131[v80[1261 -(1043 + 214) ]];break;end end end elseif ((3574==3574) and (v81<=(26 -19))) then v72=v80[1215 -(323 + (2116 -(322 + 905))) ];elseif (v81>(21 -13)) then do return;end else v78[v80[582 -((597 -(141 + 95)) + 219) ]]=v80[3];end elseif (v81<=(334 -(53 + 0 + 267))) then if (v81<=(3 + 8)) then if (v81==((1088 -665) -((36 -21) + 398))) then v78[v80[984 -(18 + 964) ]]=v78[v80[11 -(619 -(602 + 9)) ]];else local v135=0 + 0 ;local v136;local v137;local v138;local v139;while true do if ((221<390) and ((2 + 0)==v135)) then for v213=v136,v73 do local v214=850 -(20 + 830) ;while true do if (v214==(0 + 0)) then v139=v139 + (127 -(116 + 10)) ;v78[v213]=v137[v139];break;end end end break;end if ((0==v135) or (2213<=1421)) then v136=v80[1 + 1 ];v137,v138=v71(v78[v136](v13(v78,v136 + (739 -(542 + 196)) ,v80[6 -3 ])));v135=1 + 0 ;end if ((3058<4860) and ((1 + 0 + 0)==v135)) then v73=(v138 + v136) -1 ;v139=0 + (0 -0) ;v135=4 -2 ;end end end elseif ((v81<=(30 -18)) or (1296>=4446)) then local v140=v80[1553 -(792 + 334 + 425) ];local v141,v142=v71(v78[v140](v13(v78,v140 + ((212 + 194) -(118 + 287)) ,v80[11 -(1197 -(449 + 740)) ])));v73=(v142 + v140) -(873 -(826 + 46)) ;local v143=(2068 -(245 + 702)) -(118 + 1003) ;for v167=v140,v73 do v143=v143 + (2 -1) ;v78[v167]=v141[v143];end elseif (v81>(390 -(142 + (330 -95)))) then local v178=v80[2];v78[v178](v78[v178 + (4 -3) ]);else v78[v80[2]]=v78[v80[3]];end elseif (v81<=16) then if (v81==(4 + 11)) then local v144=v80[979 -(553 + 424) ];v78[v144]=v78[v144]();else for v170=v80[2],v80[5 -2 ] do v78[v170]=nil;end end elseif (v81<=17) then v72=v80[3 + 0 ];elseif ((v81>(11 + 7)) or (1393>4489)) then v78[v80[2 + 0 ]]=v29(v69[v80[3]],nil,v64);elseif (v78[v80[2 + 0 ]]==v80[2 + (6 -4) ]) then v72=v72 + 1 ;else v72=v80[3];end elseif ((v81<=(17 + 4 + 8)) or (4424<27)) then if ((v81<=((1949 -(260 + 1638)) -27)) or (1997>3815)) then if (v81<=(58 -37)) then if (v81>(44 -24)) then v78[v80[1 + 1 ]]=v64[v80[3]];else v78[v80[2]]={};end elseif (v81<=(106 -(524 -(382 + 58)))) then v78[v80[2]]=v78[v80[(919 -(92 + 71)) -(239 + 514) ]][v80[2 + 2 ]];elseif ((3465>1913) and (v81==23)) then v78[v80[2]]=v78[v80[1332 -(797 + 532) ]][v80[3 + 1 ]];else local v184=0 + 0 ;local v185;while true do if ((733<1819) and ((0 -0)==v184)) then v185=v80[(3862 -2658) -(373 + 829) ];v78[v185](v13(v78,v185 + (732 -(476 + 255)) ,v80[1133 -(369 + 761) ]));break;end end end elseif (v81<=26) then if (v81>(15 + 9 + 1)) then local v152=0 -(0 + 0) ;local v153;while true do if ((0 -0)==v152) then v153=v80[2];v78[v153]=v78[v153]();break;end end else v78[v80[240 -(64 + (359 -185)) ]][v80[(2 -1) + 2 ]]=v78[v80[5 -1 ]];end elseif (v81<=27) then local v156=v80[338 -(144 + 192) ];v78[v156]=v78[v156](v13(v78,v156 + (217 -(42 + 174)) ,v73));elseif (v81>((787 -(574 + 191)) + 5 + 1)) then do return;end else v78[v80[2 + 0 ]][v80[(4 -2) + 1 ]]=v80[1508 -(363 + 583 + 558) ];end elseif ((v81<=(1614 -((2388 -(902 + 303)) + 397))) or (4395==4755)) then if (v81<=(94 -63)) then if (v81==(22 + 8)) then v78[v80[2]]=v80[3];elseif (v80[2 + 0 ]==v78[v80[1979 -(1913 + (135 -73)) ]]) then v72=v72 + 1 + 0 ;else v72=v80[3];end elseif (v81<=(84 -52)) then local v160=v80[1935 -(565 + 1368) ];v78[v160]=v78[v160](v13(v78,v160 + 1 ,v80[11 -8 ]));elseif (v81==(1694 -(1477 + 184))) then v78[v80[2 -0 ]][v80[3]]=v78[v80[4 + 0 ]];else for v207=v80[851 -(254 + 595) ],v80[859 -(564 + 292) ] do v78[v207]=nil;end end elseif ((v81<=(61 -25)) or (3793<2369)) then if ((v81==35) or (4084==265)) then local v162=0 -0 ;local v163;while true do if ((4358==4358) and (v162==(304 -(244 + 60)))) then v163=v80[2 + 0 ];v78[v163]=v78[v163](v13(v78,v163 + (477 -(41 + (1047 -612))) ,v80[1004 -(938 + 63) ]));break;end end else local v164=v80[2 + 0 ];v78[v164]=v78[v164](v13(v78,v164 + (1126 -((1062 -(55 + 71)) + (248 -59))) ,v73));end elseif (v81<=(13 + 24)) then v78[v80[1615 -(1565 + 48) ]]=v29(v69[v80[3]],nil,v64);elseif (v81>(1828 -(573 + 1217))) then local v191=v80[2 + 0 ];local v192=v78[v80[1141 -(68 + 714 + 356) ]];v78[v191 + (268 -(176 + 91)) ]=v192;v78[v191]=v192[v80[(27 -17) -6 ]];else local v196=v80[2 -0 ];v78[v196](v78[v196 + 1 ]);end v72=v72 + (1093 -(975 + 117)) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!243Q00028Q00026Q000840026Q00F03F026Q00104003073Q004D616B6554616203043Q004E616D6503043Q004D61696E03043Q0049636F6E03173Q00726278612Q73657469643A2Q2F2Q34382Q3334352Q3938030B3Q005072656D69756D4F6E6C790100030A3Q00412Q6453656374696F6E03093Q00412Q6442752Q746F6E030C3Q004265636F6D652041646D696E03083Q0043612Q6C6261636B030B3Q00436C6F73652070616E656C030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q7470476574033D3Q00682Q7470733A2Q2F7261772E67697468756275736572636F6E74656E742E636F6D2F73686C6578776172652F4F72696F6E2F6D61696E2F736F75726365030A3Q004D616B6557696E646F77032A3Q0057686F2049732074686520537079207C204D616465206279204578706C6F69746D616E73637269707473030B3Q00486964655072656D69756D030A3Q0053617665436F6E6669672Q01030C3Q00436F6E666967466F6C64657203093Q004F72696F6E54657374027Q0040030C3Q00412Q6450617261677261706803193Q004D616465206279204578706C6F69746D616E7363726970747303343Q00446F6E742074727920746F20736B6964207468697320736372697074203A2920596F75206861766520622Q656E207761726E656403083Q00446973636F72643A03113Q004D724261636F6E627574696D62726F6B65030B3Q00496E666F726D6174696F6E03053Q004E6F74653A03243Q0054686973206120563120536372697074207468617420696E20646576656C6F706D656E74005E3Q0012083Q00014Q0022000100043Q0026123Q0019000100020004113Q00190001001208000500013Q00261200050009000100030004113Q000900010012083Q00043Q0004113Q00190001000E0400010005000100050004113Q000500010020270006000200054Q00083Q000300301C00080006000700301C00080008000900301C0008000A000B2Q00200006000800022Q000A000300063Q00202700060003000C4Q00083Q000100301C0008000600072Q00200006000800022Q000A000400063Q001208000500033Q0004113Q000500010026123Q0028000100040004113Q0028000100202700050003000D4Q00073Q000200301C00070006000E00022500085Q0010210007000F00082Q001800050007000100202700050003000D4Q00073Q000200301C000700060010000225000800013Q0010210007000F00082Q00180005000700010004113Q005D00010026123Q0043000100010004113Q00430001001208000500013Q0026120005002F000100030004113Q002F00010012083Q00033Q0004113Q00430001000E040001002B000100050004113Q002B0001001206000600113Q001206000700123Q002027000700070013001208000900144Q000B000700094Q002400063Q00022Q001A0006000100022Q000A000100063Q0020270006000100154Q00083Q000400301C00080006001600301C00080017000B00301C00080018001900301C0008001A001B2Q00200006000800022Q000A000200063Q001208000500033Q0004113Q002B00010026123Q004E0001001C0004113Q004E000100202700050003001D0012080007001E3Q0012080008001F4Q001800050008000100202700050003001D001208000700203Q001208000800214Q00180005000800010012083Q00023Q0026123Q0002000100030004113Q000200010020270005000200054Q00073Q000300301C00070006002200301C00070008000900301C0007000A000B2Q00200005000700022Q000A000300053Q00202700050003001D001208000700233Q001208000800244Q00180005000800010012083Q001C3Q0004113Q000200012Q00093Q00013Q00023Q000F3Q00028Q00026Q00F03F03053Q007072696E74030E3Q0062752Q746F6E207072652Q73656403043Q0067616D65030A3Q004765745365727669636503073Q00506C6179657273030B3Q004C6F63616C506C6179657203093Q00506C6179657247756903093Q00496E7465726661636503043Q004D61696E030A3Q0061646D696E4672616D6503063Q004163746976652Q0103073Q0056697369626C6500203Q0012083Q00013Q0026123Q0007000100020004113Q00070001001206000100033Q001208000200044Q00260001000200010004113Q001F00010026123Q0001000100010004113Q00010001001206000100053Q002027000100010006001208000300074Q002000010003000200201700010001000800201700010001000900201700010001000A00201700010001000B00201700010001000C00301C0001000D000E001206000100053Q002027000100010006001208000300074Q002000010003000200201700010001000800201700010001000900201700010001000A00201700010001000B00201700010001000C00301C0001000F000E0012083Q00023Q0004113Q000100012Q00093Q00017Q000F3Q00028Q0003043Q0067616D65030A3Q004765745365727669636503073Q00506C6179657273030B3Q004C6F63616C506C6179657203093Q00506C6179657247756903093Q00496E7465726661636503043Q004D61696E030A3Q0061646D696E4672616D6503063Q00416374697665010003073Q0056697369626C65026Q00F03F03053Q007072696E74030E3Q0062752Q746F6E207072652Q736564002E3Q0012083Q00014Q0022000100013Q0026123Q0002000100010004113Q00020001001208000100013Q000E0400010024000100010004113Q00240001001208000200013Q0026120002001F000100010004113Q001F0001001206000300023Q002027000300030003001208000500044Q002000030005000200201700030003000500201700030003000600201700030003000700201700030003000800201700030003000900301C0003000A000B001206000300023Q002027000300030003001208000500044Q002000030005000200201700030003000500201700030003000600201700030003000700201700030003000800201700030003000900301C0003000C000B0012080002000D3Q002612000200080001000D0004113Q000800010012080001000D3Q0004113Q002400010004113Q00080001002612000100050001000D0004113Q000500010012060002000E3Q0012080003000F4Q00260002000200010004113Q002D00010004113Q000500010004113Q002D00010004113Q000200012Q00093Q00017Q00",v9(),...);