# Snapshot report for `src/__tests__/type-conversion-spec.js`

The actual snapshot is saved in `type-conversion-spec.js.snap`.

Generated by [AVA](https://ava.li).

## typecasts work

> Snapshot 1

    `00000000:         6d736100 ; \\0asm␊
    00000004:                1 ; version 1␊
    00000008:                1 ; Types section␊
    00000009:               18 ; size␊
    0000000a:                5 ; count␊
    0000000b:               60 ; func type (0)␊
    0000000c:                0 ; parameter count␊
    0000000d:                1 ; result count␊
    0000000e:               7d ; result type f32␊
    0000000f:               60 ; func type (1)␊
    00000010:                1 ; parameter count␊
    00000011:               7f ; param␊
    00000012:                1 ; result count␊
    00000013:               7d ; result type f32␊
    00000014:               60 ; func type (2)␊
    00000015:                1 ; parameter count␊
    00000016:               7d ; param␊
    00000017:                1 ; result count␊
    00000018:               7f ; result type i32␊
    00000019:               60 ; func type (3)␊
    0000001a:                0 ; parameter count␊
    0000001b:                1 ; result count␊
    0000001c:               7f ; result type i32␊
    0000001d:               60 ; func type (4)␊
    0000001e:                1 ; parameter count␊
    0000001f:               7c ; param␊
    00000020:                1 ; result count␊
    00000021:               7d ; result type f32␊
    00000022:                3 ; Functions section␊
    00000023:                8 ; size␊
    00000024:                7 ; count␊
    00000025:                0 ; type index␊
    00000026:                1 ; type index␊
    00000027:                2 ; type index␊
    00000028:                1 ; type index␊
    00000029:                3 ; type index␊
    0000002a:                4 ; type index␊
    0000002b:                0 ; type index␊
    0000002c:                7 ; Exports section␊
    0000002d:               74 ; size␊
    0000002e:                7 ; count␊
    0000002f:                8 ; field␊
    00000030:               63 ; c␊
    00000031:               6f ; o␊
    00000032:               6e ; n␊
    00000033:               73 ; s␊
    00000034:               74 ; t␊
    00000035:               61 ; a␊
    00000036:               6e ; n␊
    00000037:               74 ; t␊
    00000038:                0 ; Global␊
    00000039:                0 ; index␊
    0000003a:               10 ; field␊
    0000003b:               76 ; v␊
    0000003c:               61 ; a␊
    0000003d:               72 ; r␊
    0000003e:               69 ; i␊
    0000003f:               61 ; a␊
    00000040:               62 ; b␊
    00000041:               6c ; l␊
    00000042:               65 ; e␊
    00000043:               54 ; T␊
    00000044:               79 ; y␊
    00000045:               70 ; p␊
    00000046:               65 ; e␊
    00000047:               63 ; c␊
    00000048:               61 ; a␊
    00000049:               73 ; s␊
    0000004a:               74 ; t␊
    0000004b:                0 ; Global␊
    0000004c:                1 ; index␊
    0000004d:                e ; field␊
    0000004e:               5f ; _␊
    0000004f:               33 ; 3␊
    00000050:               32 ; 2␊
    00000051:               49 ; I␊
    00000052:               6e ; n␊
    00000053:               74 ; t␊
    00000054:               54 ; T␊
    00000055:               79 ; y␊
    00000056:               70 ; p␊
    00000057:               65 ; e␊
    00000058:               63 ; c␊
    00000059:               61 ; a␊
    0000005a:               73 ; s␊
    0000005b:               74 ; t␊
    0000005c:                0 ; Global␊
    0000005d:                2 ; index␊
    0000005e:               10 ; field␊
    0000005f:               5f ; _␊
    00000060:               33 ; 3␊
    00000061:               32 ; 2␊
    00000062:               46 ; F␊
    00000063:               6c ; l␊
    00000064:               6f ; o␊
    00000065:               61 ; a␊
    00000066:               74 ; t␊
    00000067:               54 ; T␊
    00000068:               79 ; y␊
    00000069:               70 ; p␊
    0000006a:               65 ; e␊
    0000006b:               63 ; c␊
    0000006c:               61 ; a␊
    0000006d:               73 ; s␊
    0000006e:               74 ; t␊
    0000006f:                0 ; Global␊
    00000070:                3 ; index␊
    00000071:                e ; field␊
    00000072:               5f ; _␊
    00000073:               36 ; 6␊
    00000074:               34 ; 4␊
    00000075:               49 ; I␊
    00000076:               6e ; n␊
    00000077:               74 ; t␊
    00000078:               54 ; T␊
    00000079:               79 ; y␊
    0000007a:               70 ; p␊
    0000007b:               65 ; e␊
    0000007c:               63 ; c␊
    0000007d:               61 ; a␊
    0000007e:               73 ; s␊
    0000007f:               74 ; t␊
    00000080:                0 ; Global␊
    00000081:                4 ; index␊
    00000082:               10 ; field␊
    00000083:               5f ; _␊
    00000084:               36 ; 6␊
    00000085:               34 ; 4␊
    00000086:               46 ; F␊
    00000087:               6c ; l␊
    00000088:               6f ; o␊
    00000089:               61 ; a␊
    0000008a:               74 ; t␊
    0000008b:               54 ; T␊
    0000008c:               79 ; y␊
    0000008d:               70 ; p␊
    0000008e:               65 ; e␊
    0000008f:               63 ; c␊
    00000090:               61 ; a␊
    00000091:               73 ; s␊
    00000092:               74 ; t␊
    00000093:                0 ; Global␊
    00000094:                5 ; index␊
    00000095:                a ; field␊
    00000096:               70 ; p␊
    00000097:               72 ; r␊
    00000098:               6f ; o␊
    00000099:               6d ; m␊
    0000009a:               6f ; o␊
    0000009b:               74 ; t␊
    0000009c:               69 ; i␊
    0000009d:               6f ; o␊
    0000009e:               6e ; n␊
    0000009f:               73 ; s␊
    000000a0:                0 ; Global␊
    000000a1:                6 ; index␊
    000000a2:                a ; Code section␊
    000000a3:               6a ; size␊
    000000a4:                7 ; function count␊
    000000a5:                8 ; Function constant␊
    000000a6:                0 ; locals count␊
    000000a7:               43 ; f32.const  ␊
    000000a8:              0.8 ; f32.literal␊
    000000ac:                f ; return  ␊
    000000ad:                b ; end␊
    000000ae:                c ; Function variableTypecast␊
    000000af:                0 ; locals count␊
    000000b0:               20 ; get_local  x<i32>␊
    000000b1:                0 ; i32.literal␊
    000000b2:               b2 ; f32.convert_s/i32  ␊
    000000b3:               43 ; f32.const  ␊
    000000b4:                5 ; f32.literal␊
    000000b8:               92 ; f32.add  ␊
    000000b9:                f ; return  ␊
    000000ba:                b ; end␊
    000000bb:                9 ; Function _32IntTypecast␊
    000000bc:                0 ; locals count␊
    000000bd:               20 ; get_local  x<f32>␊
    000000be:                0 ; i32.literal␊
    000000bf:               a8 ; i32.trunc_s/f32  ␊
    000000c0:               41 ; i32.const  ␊
    000000c1:                2 ; i32.literal␊
    000000c2:               6a ; i32.add  ␊
    000000c3:                f ; return  ␊
    000000c4:                b ; end␊
    000000c5:               12 ; Function _32FloatTypecast␊
    000000c6:                0 ; locals count␊
    000000c7:               43 ; f32.const  ␊
    000000c8:              2.8 ; f32.literal␊
    000000cc:               20 ; get_local  x<i32>␊
    000000cd:                0 ; i32.literal␊
    000000ce:               b2 ; f32.convert_s/i32  ␊
    000000cf:               92 ; f32.add  ␊
    000000d0:               43 ; f32.const  ␊
    000000d1:              0.8 ; f32.literal␊
    000000d5:               92 ; f32.add  ␊
    000000d6:                f ; return  ␊
    000000d7:                b ; end␊
    000000d8:               10 ; Function _64IntTypecast␊
    000000d9:                1 ; locals count␊
    000000da:                1 ; number of locals of following type␊
    000000db:               7e ; i64␊
    000000dc:               42 ; i64.const  ␊
    000000dd:                2 ; i32.literal␊
    000000de:               21 ; set_local  x<i64>␊
    000000df:                0 ; i32.literal␊
    000000e0:               41 ; i32.const  ␊
    000000e1:                2 ; i32.literal␊
    000000e2:               ac ; i64.extend_s/i32  ␊
    000000e3:               20 ; get_local  x<i64>␊
    000000e4:                0 ; i32.literal␊
    000000e5:               7e ; i64.mul  ␊
    000000e6:               a7 ; i32.wrap/i64  ␊
    000000e7:                f ; return  ␊
    000000e8:                b ; end␊
    000000e9:                a ; Function _64FloatTypecast␊
    000000ea:                0 ; locals count␊
    000000eb:               41 ; i32.const  ␊
    000000ec:                2 ; i32.literal␊
    000000ed:               b7 ; f64.convert_s/i32  ␊
    000000ee:               20 ; get_local  x<f64>␊
    000000ef:                0 ; i32.literal␊
    000000f0:               a2 ; f64.mul  ␊
    000000f1:               b6 ; f32.demote/f64  ␊
    000000f2:                f ; return  ␊
    000000f3:                b ; end␊
    000000f4:               19 ; Function promotions␊
    000000f5:                0 ; locals count␊
    000000f6:               43 ; f32.const  ␊
    000000f7:              2.8 ; f32.literal␊
    000000fb:               41 ; i32.const  ␊
    000000fc:                2 ; i32.literal␊
    000000fd:               b2 ; f32.convert_s/i32  ␊
    000000fe:               92 ; f32.add  ␊
    000000ff:               43 ; f32.const  ␊
    00000100:              0.8 ; f32.literal␊
    00000104:               41 ; i32.const  ␊
    00000105:                a ; i32.literal␊
    00000106:               41 ; i32.const  ␊
    00000107:                5 ; i32.literal␊
    00000108:               6d ; i32.div_s  ␊
    00000109:               b2 ; f32.convert_s/i32  ␊
    0000010a:               94 ; f32.mul  ␊
    0000010b:               92 ; f32.add  ␊
    0000010c:                f ; return  ␊
    0000010d:                b ; end␊
     ============ fin =============`