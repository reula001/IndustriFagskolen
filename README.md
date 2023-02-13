# Industri-Fagskolen

# Test
* Dette ser ut til å fungere

```Csharp
btest := TRUE;
IF TRUE THEN
	FALSE;
END_IF;
````
## FLow chart test
```mermaid
graph TD
A(START) --> B(Check Temperature);
B-->C{Is the room hot?};
C-->|Yes|D(Turn on Aircon);
C-->|No|E(Turn of Aircon);
```

## Structured text test
```iecst
//Testing IF statement
IF _bTest THEN
	_bTest := FALSE;
END_IF;
```

