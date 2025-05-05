---
api_tags:
- class
categories:
- api
- testlib API
contributors:
- Elwardi
date: '2025-05-05'
description: 'a child model mimiking original OpenFOAM child models

  and keeping an optional subModel that participates in RTS'
foamCD:
  ctors:
  - access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L22-L22
    documentation:
      deprecated: ''
      description: Construct from dictionary
      returns: ''
      since: ''
    is_const: false
    is_constructor: true
    is_defaulted: false
    is_deleted: false
    is_deprecated: 0
    is_destructor: false
    is_final: false
    is_noexcept: false
    is_override: false
    is_pure_virtual: false
    is_static: false
    is_virtual: false
    name: childFullReflectedModel
    parameters: []
    return_type: null
    signature: explicit childFullReflectedModel(const dictionary& dict)
  documentation:
    deprecated: ''
    description: 'a child model mimiking original OpenFOAM child models

      and keeping an optional subModel that participates in RTS'
    is_deprecated: false
    params: {}
    returns: ''
    since: ''
  dtor:
    access: public
    definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L25-L25
    documentation:
      deprecated: ''
      description: Destruct childFullReflectedModels
      returns: ''
      since: ''
    is_const: false
    is_constructor: false
    is_defaulted: false
    is_deleted: false
    is_deprecated: 0
    is_destructor: true
    is_final: false
    is_noexcept: false
    is_override: false
    is_pure_virtual: false
    is_static: false
    is_virtual: false
    name: ~childFullReflectedModel
    parameters: []
    return_type: null
    signature: virtual ~childFullReflectedModel() = default
  enclosed_entities: []
  factory_methods: []
  fields:
    private: []
    protected: []
    public: []
  filename: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L11-L37
  interface:
    abstract_in_base_methods: []
    abstract_methods: []
    public_bases: []
    public_methods:
    - access: public
      name: type
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L19-L19
        documentation:
          deprecated: ''
          description: Runtime type name
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 1
        name: type
        parameters: []
        return_type: void
        signature: virtual void type()
    - access: public
      name: clone
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L28-L28
        documentation:
          deprecated: ''
          description: Update childFullReflectedModel
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 1
        name: clone
        parameters: []
        return_type: void
        signature: virtual autoPtr<fullReflectedModel> clone() const
    - access: public
      name: verifyType
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L31-L33
        documentation:
          deprecated: ''
          description: Verify type name
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 0
        is_virtual: 1
        name: verifyType
        parameters: []
        return_type: void
        signature: virtual word verifyType() const
    static_methods:
    - name: typeName_
      overloads:
      - access: public
        definition_file: https://github.com/FoamScience/openfoam-reflections/blob/wrap/src/testlib/lvl2Support/childFullReflectedModel/childFullReflectedModel.H#L19-L19
        documentation:
          deprecated: ''
          description: Runtime type name
          returns: ''
          since: ''
        is_const: false
        is_constructor: false
        is_defaulted: 0
        is_deleted: false
        is_deprecated: 0
        is_destructor: false
        is_final: 0
        is_noexcept: false
        is_override: 0
        is_pure_virtual: 0
        is_static: 1
        is_virtual: 0
        name: typeName_
        parameters: []
        return_type: void
        signature: static void typeName_()
  knowledge_requirements:
  - classes
  - default_delete
  - inheritance
  - openfoam_basics
  member_type_aliases:
    private: []
    protected: []
    public: []
  mpi_comms:
    handles_member_reference_through_mpi: false
    has_member_reference: false
    linked_lists: false
    parallel_streams: false
    random_access_lists: false
  namespace: Foam
  openfoam_dsl:
    RTS:
      RTS_table_names: []
      base_RTS_classes: []
      class_role: unknown
      is_RTS_base: false
      is_RTS_child: false
      plugin_active: true
      rts_status: partial
    reflection:
      is_reflectable: false
      reflection_error: ''
      reflection_type: ''
      standard_config: ''
      standard_config_details: ''
  private_bases: []
  private_methods: []
  protected_bases: []
  protected_methods: []
  signature: 'class childFullReflectedModel : public fullReflectedModel'
  standard_config: ''
  unit_tests: []
layout: class
title: childFullReflectedModel
url: /api/Foam_childFullReflectedModel
weight: 20
---