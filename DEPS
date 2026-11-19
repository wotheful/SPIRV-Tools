use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '5e3d5a86ffd7d454f6d5c23a16682bdb501f256f',

  'effcee_revision': '8ce15c424e61a94ee27b5be0ec0ed036b158e6e3',

  'googletest_revision': 'a46a6012a133c7c0929fdae55b321c2fe65f3c5f',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': '2da0056814cf180480a19f5cf811e7e1c054bf6d',

  'spirv_headers_revision': '50184103b19027f5c7080060712d6a9470cf59ee',
}

deps = {
  'external/abseil_cpp':
      Var('github') + '/abseil/abseil-cpp.git@' + Var('abseil_revision'),

  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/protobuf':
      Var('github') + '/protocolbuffers/protobuf.git@' + Var('protobuf_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),
}

