# GFT-AWS-fundamentos
Aprenda do zero como construir soluções em nuvem com a Amazon Web ServicDomine os fundamentos de cloud computing, configure ambientes na AWS, crie e gerencie instâncias com EC2.e com armazenamento em nuvem e aplique boas práticas de segurança e arquitetura em projetos práticos.

# Configure AWS CLI com credenciais
aws configure

# Lance instância
aws ec2 run-instances \
  --image-id ami-098e39bafa7e7303d \
  --count 1 \
  --instance-type t3.micro \
  --key-name GFT - Fundamentos de Cloud com AWS \
  --security-group-ids sg-00831892aea5b4fbc \
  --subnet-id subnet-021e099b16686ebcd

# Descreva instâncias
aws ec2 describe-instances

# Termine instância
aws ec2 terminate-instances --instance-ids 
i-0e19fcb8c8c352480
