# SPEC-config
SPEC compile



### Compiler Version(gcc/g++/gfortran)

riscv
*	spec06: 9.2.0
*	spec17: 9.2.0

x86
*	spec06: 4.8,5
*	spec17: 7.5.0 
	

### run

spec06

*	runspec --config=???.cfg --action setup/run ???
>   defualt: --size=ref (ref\test\train)
>            --tune=base (base\ref\all)

spec17

*	runcpu  --config=???.cfg --action setup/run ???
>   defualt: --size=ref (ref\test\train)
>            --tune=base (base\ref\all)

### status

riscv-spec06

	ok
	416:add -std-legacy in FORTIMIZE

riscv-spec17

	unknown

x86-spec06

	unknown

x86-spec17

	intrate :  ok
	
	intspeed:  ok
	
	fprate  :  ok 
	
	fpspeed :
	603:  error
	627:  error
	649:  error
	654:  error



