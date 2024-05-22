# Personas

## Persona 1
- **João Silva**
- 35 anos
- *Gerente*

## Persona 2
- __Maria Oliveira__
- 28 amos
- _Desemvolvedora de software_


## Persona 3
![](https://sitefactory.com.br/wp-content/uploads/2021/11/o-que-e-persona-960x550.jpg)


## Persona 4


```

class SplashFragment : Fragment() {

    private var _binding: FragmentSplashBinding? = null
    // This property is only valid between onCreateView and
    // onDestroyView.
    private val binding get() = _binding!!

    override fun onCreateView(
        inflater: LayoutInflater, container: ViewGroup?,
        savedInstanceState: Bundle?
    ): View {
        _binding = FragmentSplashBinding.inflate(inflater, container, false)
        return binding.root
    }

    override fun onViewCreated(view: View, savedInstanceState: Bundle?) {
        super.onViewCreated(view, savedInstanceState)
        Handler(Looper.getMainLooper()).postDelayed(this::checkAuth, 3000)
    }

    private fun checkAuth() {
        findNavController().navigate(R.id.action_splashFragment_to_loginFragment)

    }

```

## Tabela

| controle_estoque | 
|------------------|
|Cabeçalho|Ref|

## Referências

>  XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

> YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY 
  


  

