# the_thing_it_says_i_can_copy
This is what i get when i click the button
Exception in RimWorld.FloatMenuMakerMap.ChoicesAtFor: System.InvalidOperationException: Nothing to install.
  at RimWorld.Blueprint_Install.get_MiniToInstallOrBuildingToReinstall () [0x0001e] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.GenConstruct.MiniToInstallOrBuildingToReinstall (RimWorld.Blueprint b) [0x0000a] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.GenConstruct.FirstBlockingThing (Verse.Thing constructible, Verse.Pawn pawnToIgnore) [0x0000a] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.WorkGiver_ConstructDeliverResourcesToBlueprints.JobOnThing (Verse.Pawn pawn, Verse.Thing t, System.Boolean forced) [0x0007b] in <95de19971c5d40878d8742747904cdcd>:0 
     - prefix rimworld.erdelf.minify_everything: Boolean MinifyEverything.MinifyEverything:JobOnThingPrefix(Pawn pawn, Thing t)
  at RimWorld.WorkGiver_Scanner.HasJobOnThing (Verse.Pawn pawn, Verse.Thing t, System.Boolean forced) [0x00000] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.FloatMenuMakerMap.AddJobGiverWorkOrders (UnityEngine.Vector3 clickPos, Verse.Pawn pawn, System.Collections.Generic.List`1[T] opts, System.Boolean drafted) [0x0020d] in <95de19971c5d40878d8742747904cdcd>:0 
     - transpiler net.pardeike.rimworld.mods.achtung: IEnumerable`1 AchtungMod.FloatMenuMakerMap_AddJobGiverWorkOrders_Patch:Transpiler(IEnumerable`1 instructions)
     - prefix VanillaExpanded.VFEA: Void VFEAncients.PowerWorker_NoPrioritize:StoreOpts(List`1 opts, List`1& __state, Pawn pawn)
     - prefix net.pardeike.rimworld.mods.achtung: Void AchtungMod.FloatMenuMakerMap_AddJobGiverWorkOrders_Patch:Prefix(Pawn pawn, ForcedWork& __state)
     - postfix VanillaExpanded.VFEA: Void VFEAncients.PowerWorker_NoPrioritize:DisableOpts(List`1 opts, List`1 __state, Pawn pawn)
     - postfix net.pardeike.rimworld.mods.achtung: Void AchtungMod.FloatMenuMakerMap_AddJobGiverWorkOrders_Patch:Postfix(Pawn pawn, ForcedWork __state)
  at RimWorld.FloatMenuMakerMap.AddUndraftedOrders (UnityEngine.Vector3 clickPos, Verse.Pawn pawn, System.Collections.Generic.List`1[T] opts) [0x00085] in <95de19971c5d40878d8742747904cdcd>:0 
  at RimWorld.FloatMenuMakerMap.ChoicesAtFor (UnityEngine.Vector3 clickPos, Verse.Pawn pawn, System.Boolean suppressAutoTakeableGoto) [0x00108] in <95de19971c5d40878d8742747904cdcd>:0 
     - postfix OskarPotocki.VFECore: Void VFE.Mechanoids.HarmonyPatches.FloatMenuMakerMap_ChoicesAtFor_Patch:Postfix(List`1& __result, Vector3 clickPos, Pawn pawn, Boolean suppressAutoTakeableGoto)
     - postfix GiddyUp: Void GiddyUp.Harmony.FloatMenuMakerMap_ChoicesAtFor:Postfix(Vector3 clickPos, Pawn pawn, List`1 __result)
     - postfix net.pardeike.rimworld.mods.achtung: Void AchtungMod.FloatMenuMakerMap_ChoicesAtFor_Postfix:Postfix(List`1 __result, Vector3 clickPos, Pawn pawn)
     - finalizer net.pardeike.rimworld.mods.achtung: Exception AchtungMod.FloatMenuMakerMap_ChoicesAtFor_Finalizer:Finalizer(Exception __exception, List`1& __result)

// it says "Nothing to install." so i guess my minify everything guess was correct.
