# Mass deprecation BotController C#
*(serão removidos pós-OBR estadual e robocup, adaptem seus códigos C#)*

+ onTF(...) => MoveFrontal(...)
+ wait(...) => Wait(...)
+ move(...) => MoveFrontal(...)
+ turnActuatorDown(...) => TurnActuatorDown(...)
+ turnActuatorUp(...) => TurnActuatorUp(...)
+ actuatorUp(...) => ActuatorUp(...)
+ actuatorDown(...) => ActuatorDown(...)
+ Fechar(...) => CloseActuator(...)
+ Abrir(...) => OpenActuator(...)
+ closeActuator(...) => CloseActuator(...)
+ openActuator(...) => OpenActuator(...)
+ changeAngleActuatorUp(...) => ChangeAngleActuatorUp(...)
+ changeAngleActuatorDown(...) => ChangeAngleActuatorDown(...)
+ activateAngleActuator(...) => ActivateAngleActuator(...)
+ actuatorSpeed(...) => ActuatorSpeed(...)
+ angleActuator(...) => AngleActuator(...)
+ turnLedOn(...) => TurnLedOn(...)
+ turnLedOff(...) => TurnLedOff(...)
+ clearLCDLine(...) => ClearConsoleLine(...)
+ clearLCD(...) => ClearConsole(...)
+ writeNumber(double) => WriteNumber(...)
+ writeText(...) => WriteText(...)
+ writeBoolean(bool) => WriteBoolean(...)
+ booleanToString(bool) => BooleanToString(...)
+ printLCD(...) => PrintConsole(...)
+ timer(...) => Timer(...)
+ resetTimer(...) => ResetTimer(...)
+ millis(...) => Millis(...)
+ detectColor(...) => DetectColor(...)
+ returnRed(...) => ReturnRed(...)
+ returnGreen(...) => ReturnGreen(...)
+ returnBlue(...) => ReturnBlue(...)
+ returnColor(...) => ReturnColor(...)
+ lightness(...) => Lightness(...)
+ stopSavingConsole(...) => StopSavingConsole(...)
+ saveLCD(...) => SaveConsole(...)
+ eraseLCDFile(...) => EraseConsoleFile(...)
+ colorSens(...) => ColorSensibility(...)
+ onTFRotations(...) => MoveFrontalRotations(...)
+ onTFRot(...) => MoveFrontalAngles(...)
+ onTFRight(...) => MoveFrontalLeft(...)
+ onTFLeft(...) => MoveFrontalLeft(...)
+ getonTFLeft(...) => GetFrontalLeftForce(...)
+ getonTFRight(...) => GetFrontalRightForce(...)
+ motorSpeed(...) => RobotSpeed(...)
+ initThread(...) => InitializeThread(...)
+ abortThread(...) => AbortThread(...)
+ endAllThreads(...) => AbortAllThreads(...)
+ heat(...) => Heat(...)
+ touch(...) => Touch(...)
+ paint(...) => Draw(...)
+ stopPainting => StopDrawing(...)
+ changePencilColor(...) => ChangePencilColor(...)
+ checkStringN(...) => ExtractCharacterFromString(...)
+ changeWave(...) => ChangeWave(...)
+ stopSound(...) => StopSound(...)
+ playNote(...) => PlayNote(...)
+ toFrequency => ToPitch(...)
+ toHertz => ToHertz(...)
+ playSoundHertz(...) => PlaySoundHertz(...)
+ playSound(...) => PlaySound(...)
+ hasVictims(...) => HasVictim(...)
+ randomLimits(...) => RandomLimits(...)
+ detectDistance(...) => DetectDistance(...)
+ inclination(...) => Inclination(...)
+ compass(...) => Compass(...)
+ distance(...) => Distance(...)
+ setTextList(...) => SetTextList(...)
+ sortTextList(...) => SortTextList(...)
+ reverseTextList(...) => ReverseTextList(...)
+ containsTextList(...) => ContainsTextList(...)
+ printTextList(...) => TextListToString(...)
+ textListSize(...) => TextListSize(...)
+ textList(...) => TextList(...)
+ removeTextList(...) => RemoveTextList(...)
+ addTextList(...) => AddTextList(...)
+ setNumberList(...) => SetNumberList(...)
+ sortNumberList(...) => SortNumberList(...)
+ reverseNumberList(...) => ReverseNumberList(...)
+ containsNumberList(...) => ContainsNumberList(...)
+ printNumberList(...) => NumberListToString(...)
+ numberListSize(...) => NumberListSize(...)
+ numberList(...) => NumberList(...)
+ removeNumberList(...) => RemoveNumberList(...)
+ addNumberList(...) => AddNumberList(...)
+ turnFanOff(...) => TurnFanOff(...)
+ turnFanOn(...) => TurnFanOn(...)
+ getPrecision(...) => GetPrecision(...)
+ setPrecision(...) => SetPrecision(...)
+ angleBucket(...) => AngleScoop(...)