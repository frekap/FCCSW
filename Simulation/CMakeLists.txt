################################################################################
# Package: Simulation
################################################################################
gaudi_subdir(Simulation v1r0)

# this declaration will not be needed in the future
gaudi_depends_on_subdirs(GaudiAlg DataObjects)

gaudi_add_module(Simulation
                 src/*.cpp
                 LINK_LIBRARIES GaudiAlgLib DataObjects)

