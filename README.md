

The best way to use these libraries is to add their paths to KiCAD's path configuration.

1. Open KiCAD
2. Select "Preferences->Configure Paths"
3. Add a new path for MOGAR_LIBS that has the path to the directory containing this README
4. Click Ok
5. Open PCBNew
6. Open "Preferences->Footprint Libraries Manager"
7. Add the library ${MOGAR_LIBS}\modules\mogar_kicad.pretty (you can give it any nickname you choose)
7.1 You can also add some of the other libraries in the same way (e.g. SparkFun)
8. Unfortunately, EESchema can't handle paths, so add the path to the symbols directory to EESchema directly  by doing the following:
8.1 Open EESchema
8.2 Select "Preferences->Component Libraries"
8.3 Add the path to the libraries directory (in this directory) to the search paths
8.4 Add whatever symbol libraries you want to this project in the "Component Libraries" pane