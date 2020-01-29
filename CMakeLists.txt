add_library(fabm_models_uhh OBJECT
            uhh_model_library.F90
            ergom_split/ergom_base.F90
            ergom_split/ergom_zoo.F90
	    ergom_split/ergom_utilities.F90
            diatoms/diatoms.F90
            phy_feedback/phy_feedback.F90
            halogen/halogen.F90
            halogen/uv.F90
           )

add_dependencies(fabm_models_uhh fabm_base)

#-----------------------------------------------------------------------
# Copyright (C) 2014 - Richard Hofmeister (Uni Hamburg)                !
#-----------------------------------------------------------------------
