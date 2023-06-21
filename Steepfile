D = Steep::Diagnostic

target :app do
  signature "sig"

  check "app"                       # Directory name
  check "Gemfile"                   # File name

  configure_code_diagnostics(D::Ruby.lenient)      # `lenient` diagnostics setting
end
