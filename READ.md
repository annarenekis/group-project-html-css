///mix////
@mixin container($wd: 100%, $ml: auto, $mr: auto, $pl: 20px, $pr: 20px) {
  width: $wd;
  margin-left: $ml;
  margin-right: $mr;
  padding-left: $pl;
  padding-right: $pr;
}

@mixin section($indent: 60px) {
  padding-top: $indent;
  padding-bottom: $indent;
}
@mixin set-items-margin($margin-direction, $margin-value) {
  margin-#{$margin-direction}: $margin-value;

  &:last-child {
    margin-#{$margin-direction}: 0;
  }
}

///placeholders///

%flex-center {
    display: flex;
    justify-content: center;
    align-items: center;
}
