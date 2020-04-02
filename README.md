# Error while instantiating a mod of type HarmonyMod.HarmonyMain: System.Reflection.TargetInvocationException: Exception has been thrown by the target of an invocation. ---> System.ExecutionEngineException: String conversion error: Illegal byte sequence encounted in the input.
  at (wrapper managed-to-native) System.Reflection.Assembly.get_code_base(System.Reflection.Assembly,bool)
  at System.Reflection.Assembly.GetCodeBase (System.Boolean escaped) [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.Assembly.get_CodeBase () [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.AssemblyName.Create (System.Reflection.Assembly assembly, System.Boolean fillCodebase) [0x00010] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.RuntimeAssembly.GetName (System.Boolean copiedName) [0x0000e] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.Assembly.GetName () [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at HarmonyLib.PatchProcessor.VersionInfo (System.Version& currentVersion) [0x00016] in <2161c8330234450b8141397c32c11571>:0 
  at HarmonyLib.Harmony.VersionInfo (System.Version& currentVersion) [0x00000] in <2161c8330234450b8141397c32c11571>:0 
  at HarmonyMod.HarmonyMain..ctor (Verse.ModContentPack content) [0x00007] in <5bcc4ee6da2a467bbdbae2fe2251a58b>:0 
  at (wrapper managed-to-native) System.Reflection.MonoCMethod.InternalInvoke(System.Reflection.MonoCMethod,object,object[],System.Exception&)
  at System.Reflection.MonoCMethod.InternalInvoke (System.Object obj, System.Object[] parameters) [0x00002] in <567df3e0919241ba98db88bec4c6696f>:0 
   --- End of inner exception stack trace ---
  at System.Reflection.MonoCMethod.InternalInvoke (System.Object obj, System.Object[] parameters) [0x00014] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.MonoCMethod.DoInvoke (System.Object obj, System.Reflection.BindingFlags invokeAttr, System.Reflection.Binder binder, System.Object[] parameters, System.Globalization.CultureInfo culture) [0x0007a] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.MonoCMethod.Invoke (System.Reflection.BindingFlags invokeAttr, System.Reflection.Binder binder, System.Object[] parameters, System.Globalization.CultureInfo culture) [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.RuntimeType.CreateInstanceImpl (System.Reflection.BindingFlags bindingAttr, System.Reflection.Binder binder, System.Object[] args, System.Globalization.CultureInfo culture, System.Object[] activationAttributes, System.Threading.StackCrawlMark& stackMark) [0x00213] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Activator.CreateInstance (System.Type type, System.Reflection.BindingFlags bindingAttr, System.Reflection.Binder binder, System.Object[] args, System.Globalization.CultureInfo culture, System.Object[] activationAttributes) [0x00095] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Activator.CreateInstance (System.Type type, System.Object[] args) [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at Verse.LoadedModManager.CreateModClasses () [0x00076] in <29684bdca4b441d38f64a3f064edc8ed>:0 
Verse.Log:Error(String, Boolean)
Verse.LoadedModManager:CreateModClasses()
Verse.LoadedModManager:LoadAllActiveMods()
Verse.PlayDataLoader:DoPlayLoad()
Verse.PlayDataLoader:LoadAllPlayData(Boolean)
Verse.<>c:<Start>b__6_1()
Verse.LongEventHandler:RunEventFromAnotherThread(Action)
Verse.<>c:<UpdateCurrentAsynchronousEvent>b__27_0()
System.Threading.ThreadHelper:ThreadStart_Context(Object)
System.Threading.ExecutionContext:RunInternal(ExecutionContext, ContextCallback, Object, Boolean)
System.Threading.ExecutionContext:Run(ExecutionContext, ContextCallback, Object, Boolean)
System.Threading.ExecutionContext:Run(ExecutionContext, ContextCallback, Object)
System.Threading.ThreadHelper:ThreadStart()
