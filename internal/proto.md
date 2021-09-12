protocol "MagicNum:8,SRoU Length:8,H:1,T:1,S:1,F:2,Reserve:7,ProtoID:4,Flow IP(Optional):96,Source Address Port(Optional):48,SegmentType:8,SRH Len:8"
protocol "SegmentType:8,SRH Length:8,LastEntry:8,Segment Left:8,Source Address and Port(Optional):64,SegmentList[0](Length Based on Segment Type):64, ...:96,SegmentList[N](Length Based on Segment Type):64,Optional Data (Variable):64,HMAC(If H-bit set):64"



protocol "MagicNum:8,SRoU Length:8,H:1,T:1,S:1,F:2,Reserve:7,ProtoID:4,SegmentType:8,SRH Length:8,LastEntry:8,Segment Left:8,SegmentList[0](Length Based on Segment Type):48"