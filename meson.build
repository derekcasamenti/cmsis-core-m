project('cmsis-core-m', 'c',
    license : 'Apache-2.0',
    version : '5.4.0',
    default_options : [
        'warning_level=2',
    ],
)

inc = include_directories('include', is_system : true)

cmsis_core_m_dep = declare_dependency(
    include_directories : inc,
)
