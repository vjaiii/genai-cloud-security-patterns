# LLM Threat Model

## Key assets

- User prompts
- Retrieved documents
- Model responses
- Training data
- API credentials
- Vector databases

## Trust boundaries

User → AI Application  
Application → Retrieval Layer  
Retrieval Layer → Data Sources  
Application → Model Endpoint  

## Common threats

Prompt injection  
Sensitive data leakage  
Unauthorized document retrieval  
Model misuse  
Token abuse  
API key exposure

## Security considerations

Input validation  
Content filtering  
Identity-aware access  
Audit logging  
Rate limiting  
Monitoring abnormal usage
